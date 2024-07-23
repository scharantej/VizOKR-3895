## Flask Application Design for Use data visualization to build an application that allows FSRs to achieve OKRs by viewing performance dashboards related to both sales plays and Book of Business.

### HTML Files

- **index.html**: The main HTML file that will display the performance dashboards. It will include sections for both sales plays and Book of Business, each with its own data visualization.

- **base.html**: A base HTML file that will provide a consistent layout for all pages in the application. It will include the navigation bar, header, and footer.

### Routes

- **index**: The route for the main page of the application. It will render the `index.html` file.

- **sales_plays**: The route for the sales plays dashboard. It will gather data from the database and render the data visualization in the `index.html` file.

- **book_of_business**: The route for the Book of Business dashboard. It will gather data from the database and render the data visualization in the `index.html` file.

### Implementation

1. Create the HTML files described above.
2. Define the routes in the Flask application.
3. Connect the data visualization libraries to the Flask application.
4. Set up the database connection and write queries to retrieve the necessary data.
5. Render the data visualizations in the jinja2 templates.