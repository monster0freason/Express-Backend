7.1 production grade code
7.2 using eraser.io to create models
7.3 using git ignore generators
7.4 using nodemon as dev dependencies
7.5 prettier as dev dependencies
8.1 created a a database in mongodb atlas
8.2 wrote code to connect with the database, src/db/index.js
8.3 updated the index to call the database function.
8.4 added database connection url in .env file
8.5 added database name in the constant.js
9.1 created a express app in app.js
9.2 handled connectDB promise in index.js
9.3 installed cookie-parser and cors.
9.4 added cors origin in dotenv
9.5 created ApiErrors.js in utils as the wrapper function for all the errors
9.6 created ApiResponse.js in utils as the wrapper function for all the response
9.7 created asyncHandler.js in utils as the wrapper to handle all res , req , next
10.1 created user.model.js and video.model.js in model folder
10.2 installed mongoose-aggregate-paginate-v2 as a plugin for mongoose.
10.3 installing bcrypt which helps us to encrypt the user password in database and jsonwebtoken which help us in encripting the payload.
10.4 using a pre hook from moongoose which runs a function(which uses bcrypt) on the password to encrypt it  just before it is saved.
10.5 added access_token_secret , refresh_token_secret, access_token_expiry, refresh_token_expiry in the dotenv file.
10.6 created custom method for userSchema -> isPasswordCorrecr , generateAccessToken , generateRefreshToken.
