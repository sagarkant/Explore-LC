# Cold Email Generator
Use Case : This demo shows how can we create the cold email generator tool using llm. 

## Architecture
![Untitled - Frame 1](https://github.com/user-attachments/assets/faf85a27-b248-42b4-89bb-d62eefb62b3f)

## Flow

1. Driver program will scrap the job description from the input url.
2. it will arrange the content as per job , description , level etc.
3. Chroma DB will store the already mapping of projects with git link based on skill.
4. Driver will invoke the chroma db and llm TO GENERATE THE EMAIL .
