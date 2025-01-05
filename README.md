
# Expense Management System

**Streamlit | FastAPI | Python**  
GitHub Repository: [Expense Management System](https://github.com/vivjori115)  

## Project Description  
This project is an **Expense Management System** designed to simplify expense tracking and management. The system leverages:  
- **Streamlit** for an intuitive and interactive user interface.  
- **FastAPI** for fast, secure, and reliable backend API endpoints.  
- A **MySQL database** for efficient data storage and management.  

### Key Features  
- **Real-time Expense Tracking**: Track expenses seamlessly with live updates.  
- **FastAPI Backend**: High-performance API endpoints for CRUD operations.  
- **Interactive Visualizations**: Dynamic data visualization with Streamlit.  
- **Scalable Architecture**: Easily extend the system for future enhancements.  

---

## Setup Instructions  

Follow these steps to set up and run the project on your local machine:  

### 1. Clone the Repository  
```bash  
git clone https://github.com/vivjori115/expense-management-system.git  
cd expense-management-system  
```  

### 2. Set Up the Python Environment  
Create a virtual environment and activate it:  
```bash  
python -m venv venv  
# Activate the virtual environment
# On macOS/Linux:
source venv/bin/activate  
# On Windows:
venv\Scripts\activate  
```  

Install the required dependencies:  
```bash  
pip install -r requirements.txt  
```  

### 3. Configure the Database  
- Install and start MySQL.  
- Create a database for the system.  
- Update the database configuration in the `.env` file:  
  ```dotenv  
  DB_HOST=localhost  
  DB_USER=root  
  DB_PASSWORD=yourpassword  
  DB_NAME=expense_db  
  ```  

Run the database migration script to initialize the schema:  
```bash  
python migrate.py  
```  

### 4. Start the Backend (FastAPI)  
Start the FastAPI server:  
```bash  
uvicorn main:app --reload  
```  
The API will be available at: `http://127.0.0.1:8000`  

### 5. Start the Frontend (Streamlit)  
Run the Streamlit application:  
```bash  
streamlit run app.py  
```  
The Streamlit application will be accessible at: `http://localhost:8501`  

---

## Future Enhancements  
- Add user authentication and authorization for secure access.  
- Include advanced analytics dashboards with expense trends.  
- Implement support for multiple currencies.  

---

## Contribution Guidelines  
We welcome contributions! Feel free to:  
- Submit issues and feature requests.  
- Fork the repository and create pull requests.  

---

## Contact  

**Developed By:**  
[Vivek Jori](https://www.linkedin.com/in/vivek-jori-11s/)  

**Reach Out:**  
- GitHub: [@vivjori115](https://github.com/vivjori115)  
- Email: [viv.jori11@gmail.com](mailto:viv.jori11@gmail.com)  

---  


