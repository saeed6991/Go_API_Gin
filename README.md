# Go_API_Gin
For Geting:
	curl http://localhost:8000/books



For Posting:

	curl http://localhost:8000/books --include --header "Content-Type: application/json" --request "POST" --data '{"id": "5","title": "Sapiens","writer": "Nooh","price": 20}'
