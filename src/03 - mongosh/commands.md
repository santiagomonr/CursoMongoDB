## Connect to container

´´´sh
docker-compose exec mongodb bash
'''

## Connect with mongosh

'''sh'
mongosh "mongodb+srv://santiagomonrro55_db_user:L0XZg2pAyBdw3MGe@mongodb101.f31aylt.mongodb.net/"

mongosh "mongodb://ROOT:root123@localhost:27017/?tls=false"
''

'''sh'
 show dbs
 show collections
''

'''sh'
use("platzi_store")
db.products.find()
''