# Patika - Dependency Injection
PatikaDependencyInjection is a simple C# console application demonstrating the **Dependency Injection (DI)** concept. The application models a basic classroom system where a teacher is assigned dynamically using constructor injection. By following **interface-based programming**, it ensures loose coupling between components, making the system more scalable and maintainable.


## 🚀 Project Purpose
This project demonstrates **Dependency Injection (DI)** in C# using **Constructor Injection**. The main goal is to separate concerns and improve code maintainability by injecting dependencies rather than instantiating them directly. The project simulates a basic **Classroom Management System**, where a **ClassroomService** depends on a **TeacherService** via an interface **ITeacher**.

## 🎯 Features
- Implements **Dependency Injection (DI)** without using a DI Container.
- Follows the **SOLID** principles, especially **Dependency Inversion Principle (DIP)**.
- Uses **Interfaces** to decouple the **TeacherService** from **ClassroomService**.
- Demonstrates **Constructor Injection** to pass dependencies.

## 📁 Project Structure

```
📂 PatikaDependencyInjection
│── 📂 Managers
│    ├── ClassroomService.cs
│    ├── TeacherService.cs
│
│── 📂 Services
│    ├── ITeacher.cs
│
│── Program.cs
│── README.md
```

- **Services/** → Contains the `ITeacher` interface.
- **Managers/** → Contains `TeacherService` and `ClassroomService`, responsible for handling teacher and classroom operations.
- **Program.cs** → The entry point of the application.

## 🛠️ Technologies Used
- **C#**
- **.NET Console Application**

## 🏗️ Installation and Execution
Follow these steps to run the application:

1. **Clone the project:**
   ```bash
   git clone https://github.com/ulaskarakas/PatikaDependencyInjection.git
   ```
2. **Install .NET SDK:**
   - If not already installed, download the appropriate version from the [.NET SDK](https://dotnet.microsoft.com/download) page.

3. **Navigate to the project directory and run the application:**
   ```bash
   cd PatikaDependencyInjection
   dotnet run
   ```

## 🏆 Example Output
```
Teacher: Ekrem Yılmaz
```

## 📌 Future Enhancements
- Integrate **Microsoft.Extensions.DependencyInjection** for a DI Container.
- Add multiple teacher types (e.g., `OnlineTeacher`, `PartTimeTeacher`).
- Implement logging and exception handling.

## 🤝 Contributing
To contribute to this project, please submit a **Pull Request** or create an **Issue**.

## ⚖️ License
This project is licensed under the MIT License.

## 📬 Contact
For any questions or suggestions, feel free to contact me:

[![Gmail](https://ziadoua.github.io/m3-Markdown-Badges/badges/Gmail/gmail1.svg)](mailto:ulaskarakas95@gmail.com)
[![LinkedIn](https://ziadoua.github.io/m3-Markdown-Badges/badges/LinkedIn/linkedin1.svg)](https://www.linkedin.com/in/ulas-karakas/)
