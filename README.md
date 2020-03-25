# Mercado no AR + PDM (backend)


<head>
	<h1>  DevÁgil - Mercado no Ar API</h1>
</head>
<body>
	<p align="center">
  <img src="mercado.png" width="150" title="Mercado no Ar">
</p>
<div>

  ##  Description:
   - The new 'Mercado no Ar' project is a redesign of the page to target usability and attractions for users

  ##  Running:
   - Clone code - "git clone url_repository" .
   - Running "yarn" in path .
   - Create instances docker:
        - `Postgres:` docker run --name INSTANCE_NAME -e POSTGRES_PASSWORD=PASS -p 5432:5432 -d postgres:11
        - `MongoDB:` docker run --name INSTANCE_NAME -p 27017:27017 -d -t mongo
        - `Redis:` docker run --name INSTANCE_NAME -p 6379:6379 -d -t redis:alpine
   - For better structuring of the code used, Eslint, Editor config and Prittier, installation of plugins in Vscode.

   - Create an .env file from .envexample

   - run "yarn dev" in terminal and "yarn queue" in another.

   - In insomnia import workspace file "Insomnia_request_test.json"

   ##  Technologies Used:
   - Express
   - NodeMailer
   - Multer
   - JWT
   - DotEnv
   - Bcrypt
   - Yup
   - Mongoose
   - Sequelize
   - Bee-Queue
   - Database:
        - `Postgres` - Structured Data
        - `MongoDB`  - Unstructured data / notification control
        - `Redis`    - Queue control for sending email
   - Developer:
        - `Eslint`
        - `Prittier`
        - `Editor Config`
        - `Sentry`
        - `Sucrase`
        - `Nodemon`



  ## Features:
  - Login/Create/Update User using JWT


</div>

</body>
