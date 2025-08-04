# RAG-Agent
# IMPORTANT YOU MUST CREATE YOUR OWN CREDENTIALS FOR GEMINI, GOOGLE DRIVE & PINECONE  
Automate cosmetics sales queries using RAG (Retrieval-Augmented Generation) with Pinecone and n8n.  
1. The user uploads a document to his google Drive
2. N8N detects the new document, downloads it and then uploads it to a vector database in Pinecone.
3. The user opens the N8N chat and performs the query.
4. The IA agent, executes the promt searching for the requested information in the DB, to finally provide the user with the answer.
   ## Stack
- **CREATED WITH**: n8n  
- **Vector DB**: Pinecone  
- **Embeddings**: Google Gemini  
- **Chat Interface**: n8n chat trigger
  # How to import the file
1. Download the file "RAG agent.json" from this repository.
2. In N8N create a new workflow.
3. Serach te menu with the 3 points (...) and selct the option  "Import from file".
   <img width="457" height="325" alt="image" src="https://github.com/user-attachments/assets/17a1a7cf-1d3d-4578-978a-5b93c45ea1cc" />
4. Select the file "RAG agent.json".
# Agente RAG
# IMPORTANTE USTED DEBE CREAR SUS PROPIAS CREDENCIALES PARA GEMINI, GOOGLE DRIVE Y PINECONE
Automatiza consultas sobre ventas de cosméticos usando RAG (Retrieval-Augmented Generation) con Pinecone y n8n.
1. El usuario sube un documento a su google Drive
2. N8N detecta el nuevo documento, lo descarga y posteriormente lo sube a una base de datos vectorial en Pinecone.
3. El usuario abre el chat de N8N y realiza la consulta.
4. El agente IA, ejecuta el promt buscando la información solicitada en la DB, para finalmente brindar al usuario la respuesta.
## Stack
- **Orquestación**: n8n  
- **Vector DB**: Pinecone  
- **Embeddings**: Google Gemini  
- **Chat Interface**: n8n chat trigger
   # Como importar el archivo
1. Descargar el archivo "RAG agent.json" de este repositorio
2. En N8N crear un nuevo workflow
3. Buscar el menu con los 3 puntos suspensivos (...) y seleccionar la opción "Import from file".
   <img width="457" height="325" alt="image" src="https://github.com/user-attachments/assets/17a1a7cf-1d3d-4578-978a-5b93c45ea1cc" />

4. Seleccionar el archivo  "RAG agent.json".  
#DEMO


https://github.com/user-attachments/assets/3594f751-5fc2-47b0-a2f7-1a3c2de34e10


