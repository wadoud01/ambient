## Smart Airport
Project: Smart airport
Name: Guelmami ABdelouadoud 
ID : S5467288

# What is it ?
This protege program will you show prperties of each passenger, in sense of : What gate and plane to take? The departure time, Also the service of all possible to be accessed based on the type of ticket of each passenger, and if there are overweighted lugagges their should be price to be payed.

# How to run?
Open the Airport.owl file then run from --> Reasoner/ Start reasoner

## Oveall Stracture

# Owlthing
The file is consisted of 5 main subclasses which are as follows :
  1- Airport : this Class contains all the elelmets that belongs to the aiport: Destination, Gate, Plane. Where we have 3 possible destinations Prague, Florence, Budapest. Also there 3 gates and planes respectively.  
  2- Lugagges : This Class contains 3 subclasses which are cabin and checked luagagges also small bags, each one of them are associated with a significant weight.  
  3- Passengers: It's made of 3 different age type of passengers : Adutl, eldery and Chidlren. the last two are associated with speacial needs, and 50% discount respectively.  
  4- Serivce : It describes all the services the airlines company serves, some of them are based on the types of tickets and the ages of the people.  
  5- Tickets : It describes the typse of tickets possible: 1st class, businness, economic.  
  
# Object Properties

Has : used to describes that passenger has what type of lugagges.  
Has_destination : Used to describe the destination of the passenger.  
Has_Ticket: It diffrentiates the type of tickets class that the passenger have.   
Has_accessTo : It helps to indentify the all the services could be accessed by the user.  
Has_to_GOto: it used to delcare what gate number should be .  
Has_to_GetIn: It used to declare what plane to take.  

# Data Properties
Departs_at: xsd:timeDate type used to describe the depart time of the plane .  
Has_toPay: Used to specify the has to pay if there are any overwighted lugagges  
Has_weight : It responsible about to identify the weight for each passenger.  

