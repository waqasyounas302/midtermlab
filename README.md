
This project simulates the **PostCrossing website** and includes a **Firefox extension** to sort postcard tabs.  
Features: user registration, sending/receiving postcards, reciprocal postcard logic, and tab sorting.
Question 1: 

- **Database:** MongoDB  
- **Collections:** `users`, `profiles`, `addresses`, `postcards`, `events`, `matches`  
- **Features:**  
  - Users can send/receive postcards  
  - Reciprocal postcard logic ensures a user receives a card after sending one  
  - Tracks postcard status and events  
- **Data inserted via Python scripts** 
 Question 2:
  
  - `GET /users` → List all users  
  - `GET /postcards` → List all postcards (with optional status filter)  
  - `POST /postcards/send` → Assign a postcard to a recipient  
  - `GET /matches` → Get open reciprocal matches  
  - `POST /events` → Record postcard events (sent, delivered, commented)
