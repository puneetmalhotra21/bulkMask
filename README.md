#BulkMask

How to use script

Run below code from Dev Console.

String Comma_Separted_Objects_String = Obj1,Obj2,Obj3,Obj4; 

BulkMasking bulkMask = new BulkMasking(Comma_Separted_Objects_String);
Database.execute.(bulkMask, batch_size);
