# The Holberton AIRBnB CLONE                                                                                               
![alt text](https://media.makeameme.org/created/gets-airbnb-says.jpg "fun AirB&B")             
## Description
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

## the HBNB console                                                                                                   
----
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

   -Create a new object (ex: a new User or a new Place)  
   -Retrieve an object from a file, a database etc…  
   -Do operations on objects (count, compute stats, etc…)  
   -Update attributes of an object  
   -Destroy an object  
   
## Commands and how to use it                                                                                     
the command interpreter allow us to handle our data requirements with the following commands
                                                                                                                      
| Command | Function |                                                                                                
| ------- | ------------------------------------ |
| create | create a new instace of a class |
| show | show the info of an instance of a class |
| destroy | destroy a instance of a class |
| update | update the info of the objects in an instance |
| all | update the info of the objects in an instance |
| quit | exit the console |
| help | show the help of the commands |

## Objects
this is the objects that you can pass to the command console

| Object | Function |                                                                                                
| ------- | -------- |
| city | city of the reservation |
| state | country state of the reservation |
| place | Name of the place of reservation |
| user | Name of the user who reserves|
| amenity | Benefits of the place |
| review | review of the room and the guest |

### To start using the console
start the console with
```./console```
Output:
```(hbnb)```
## How to use the HBNB console
### Syntax:
``` <command> <classname> <id>```
id is not necessary to create command
### For help:
```help <command>```
### Examples:
#### For Help:
```
(hbnb)help create
create a new instace of a class
(hbnb)
```
#### For standard commands:
```
```
creates a new User
``` 
(hbnb)create User
d3fcb371-6b66-499b-88a4-1cde2299bca2
(hbnb)

 ```
 creates a new BaseModel and show the objects of the instance
 
```
(hbnb)create BaseModel
50a99f12-2ca8-4700-b45a-767b297be6cd
(hbnb) show BaseModel 50a99f12-2ca8-4700-b45a-767b297be6cd
[BaseModel] (50a99f12-2ca8-4700-b45a-767b297be6cd) {'id': '50a99f12-2ca8-4700-b45a-767b297be6cd', 'created_at': datetime.datetime(2021, 11, 22, 1, 0, 3, 273109), 'updated_at': datetime.datetime(2021, 11, 22, 1, 0, 3, 273129)}
(hbnb) 

 ```
 Destroys BaseModel
 
```
(hbnb) destroy BaseModel 50a99f12-2ca8-4700-b45a-767b297be6cd
(hbnb) 
```
## Authors
[Mwovi Kelvin] (https://github.com/ngusya)  
[Inkingi Mugabo] (https://github.com/lmugabo)
