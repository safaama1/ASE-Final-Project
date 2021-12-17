# Split The Bill<br/>
The purpose of the app is to solve the problem that arises when several people dine together in a restaurant, get a bill, and have difficulty calculating the share of each of them .<br/> 
The app solves the problem by allowing you to scan the bill and turn it into a digital account in a matter of seconds.<br/> 
From this account, each diner can choose items according to what he has eaten, and the app calculates how much he has to pay.<br/> 
**Application Functions**:
1. Scanning the receipt and turning it into a digital list of items & prices where items can be marked and selected.
2. Sharing all users on the same digital list.
3. The user selects several items from the list and the application calculates their total price.
4. The list is updated for all users and next to each item is the name of the person who selected it.

We used socket.io to let people join or create rooms that show the items on the bill; every time a person chooses an item, the bill gets updated and shows the other users in the room that the item has been taken.<br/>
