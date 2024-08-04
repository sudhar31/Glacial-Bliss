Glacial Bliss
Slogan: Savor the Frost, Taste the Joy
Overview
Glacial Bliss is a dynamic and interactive web application designed for an ice cream restaurant. It also offers smoothies, cookies, biscuits, milkshakes, and falooda. The project uses Java Spring Boot for the backend and Angular with Bootstrap for the frontend, ensuring a robust and responsive user interface. This project demonstrates full-stack development, integrating a powerful backend with a polished and visually appealing frontend.
Project Objectives
* Backend: Java Spring Boot is used to manage the server-side logic and database interactions, ensuring efficient handling of CRUD operations for products, orders, and users.
* Database: MySQL is employed for data management, including tables for products and orders. The backend is tightly integrated with MySQL entities.
* Frontend: Angular combined with Bootstrap ensures a responsive and visually attractive user interface. CSS is used extensively for styling, hover effects, and transitions.
* Testing: Postman is utilized to test the backend APIs, ensuring the functionality of all operations before integrating the frontend.
* Security: Features like user authentication and CORS configuration are included to restrict unauthorized access and protect user data.
Features
1. Database Management:
o MySQL is used to manage data, including tables for products, orders, and users.
o CRUD operations are implemented for managing products and orders.
o CORS configuration is handled via CorsConfig.java.
2. Backend:
o Developed using Java Spring Boot.
o Integrated with MySQL to handle entities like Product, Order, and User.
o Includes comprehensive CRUD operations for the Product entity.
o Tested using Postman for API validation.
o pom.xml is configured with Maven, including the necessary plugin configurations.
3. Frontend:
o Developed using Angular and Bootstrap 5.3.3 for a responsive UI.
o Implemented CSS-only logo design, hover effects, transitions, and background images from online URLs.
o The menu list features pagination with hover zoom effects.
o Essential components like navbar, home, footer, product-details, and product-list are developed first, followed by cart, order, and user for authentication.
4. Functionality:
o Users can browse products, add them to the cart, and proceed to checkout.
o Payment options include "Pay Now" and "Cash on Delivery" (COD), with payment restricted without login or sign-up.
o Frontend is fully responsive and fits the entire page without centering content.
Project Structure
1. Spring Boot Backend:
o Entity Management: Product, Order, and User entities are managed with proper table linking using @Table annotations.
o Controller: Managed with @CrossOrigin(origins = "http://localhost:4200").
o CORS Configuration: Handled with CorsConfig.java.
o Maven Plugin: Configured with maven-surefire-plugin to handle test failures.
2. MySQL Database:
o Database and tables are set up and configured within MySQL Workbench.
o All backend operations are linked to MySQL entities.
3. Postman Testing:
o API endpoints are thoroughly tested using Postman to ensure the backend is functioning correctly.
4. Angular Frontend:
o HTML5, CSS3, and Bootstrap are used for designing the UI.
o Components for navigation, home, product details, product listing, cart, order, and user management are developed step-by-step.
o CSS is used for hover effects, transitions, and background styling.
Execution Plan
1. Step-by-Step Development:
o The project will be developed in a series of steps, each focusing on a specific part of the application.
o Spring Boot Development: Start with backend development, setting up entities, controllers, and database connections.
o Database Setup: Configure MySQL, create tables, and establish connections with the backend.
o Postman Testing: Test backend APIs thoroughly before proceeding with frontend development.
o Frontend Development: Once the backend is confirmed, start with Angular development, focusing on responsiveness and UI design.
o Final Integration: Integrate frontend with the backend and ensure all components work harmoniously.
o Documentation: Complete the project documentation in MS Word.
Technical Details
Spring Boot
* Entities: Product, Order, User - manage CRUD operations.
* Annotations: Use @Table and other relevant annotations to link tables and entities.
* Controller: Include CORS handling via @CrossOrigin.
* Maven: Configure Maven with maven-surefire-plugin for better build management.
* Image Handling: Utilize online URLs for background images.
Angular
* Components: Begin with essential components (navbar, home, footer, etc.) before moving on to more complex ones like cart and order.
* Service and Models: Structure services and models to handle data communication between the frontend and backend.
* UI/UX: Ensure responsiveness, add CSS effects, and focus on a polished user interface.
Development Environment
* IDE: Use IntelliJ IDEA for backend development and VSCode for frontend development.
* Version Control: GitHub Desktop will be used for version control. Since the project exceeds 300MB, use GitHub LFS (Large File Storage) if necessary.
Pushing to GitHub
1. Repository Setup: Create a new repository on GitHub.
2. Two Folders Setup: Backend (Spring Boot) and frontend (Angular) are in separate folders.
3. Commit & Push: Commit changes from both IntelliJ (backend) and VSCode (frontend) to the same GitHub repository using GitHub Desktop.
Conclusion
The Glacial Bliss project is a comprehensive full-stack web application with a strong focus on user experience, security, and functionality. The step-by-step development plan ensures that each aspect of the project is handled with care, from backend development to frontend design. The final product will be a polished, responsive, and fully functional web application, perfect for showcasing modern web development techniques.

