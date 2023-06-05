NOTE: 
1. Modify config according to your own keys
2. run command "docker-compose up build" from the project directory in linux environment

<-----------------------------------------------How to create duckduckgo agent------------------------------------------------->
By default the search will return top 5 results (hardcoded in code)

1. Make a new agent with any name (eg. duckduckgo_search).
2. Give it's description (eg. returns search results)
3. write text as follows for goals:
	1. "search" your_search_query_here
	2. "finish"
5. Select Model as: gpt-3.5-turbo
4. Select tool as: DuckDuckGo