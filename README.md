# Patient Management System

A Patient Management System made using Node.js (Express.js), Dgraph and Gridsome (Vue)

____

### How to setup the application locally

1) Clone the DAMS-Backend (https://github.com/webd-t31/DAMS-Backend) repo.
2) Clone the DAMS-Frontend (https://github.com/webd-t31/DAMS-Frontend) repo.
3) Make sure your system has dgraph database (https://dgraph.io/downloads/).
4) Create a empty folder for storing data (say, `data`).
5) Run `npm install` in in the root folders of both the backend and frontend repo.

### How to run the application locally

1) Run `gridsome develop --port=<PORT>` in the frontend root folder. Use any port number except for (8000 - for backend, 8080 - for database)
2) Run `node index` in the backend root folder.
3) Start the dgraph database server by running `dgraph zero` and `dgraph alpha` in different terminals with current working directory as the empty folder (`data`) that was created in step (4) of previous section.
