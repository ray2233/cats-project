run mongod.exe --->

npm run prod

localhost:3000

for mongo db:
---------------------

db
use test
show collections
use users
db.users.find().pretty()   ---- to see whats in users collection

Insert:

db.users.insertOne(
   { "_id" : ObjectId("5e14f7d7cac4435ad057b1b8"),
        "username" : "ray2234",
        "email" : "admin1@admin.com",
        "password" : "$2a$10$x6MR2Ny0.I92DWFji81Hdu3/iprJlQV1FJFO7HV1Zvdjtpv0biuLa",
        "role" : "admin",
        "__v" : 0
   }
)