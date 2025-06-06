# LLM_LAB_Tracking_of_habits

## Used Prompts

### User story 1
* Add the main file for a web that allows user to track their habits. Eventually, I will provide specific user stories about the functionalities of this web and acceptance criteria

* I want it to be in html, not react native.

* I want a separate html named (addHabits) that implements the first user story in the web: As a user, I want to define personal habits to keep track of my routines.
Acceptance Criteria:
 The functionality must be available in the main interface.
 The user must be able to undo the action if necessary.
 The system must confirm the action with a message afterward.
 All data must be saved correctly and remain accessible afterward.

* Modify the code to add a button in the main (index) to connect index with add habits

* I want you to add code such that the habits introduced are stored in a csv.

* No, I don't want the user to download a csv, but the web to have a database to keep track of the habits of the user. --> Response: When a user adds a habit, it is stored in localStorage

### User story 2

* Do a new html that implements this user story:
As a user, I want to mark habits as completed so I can track daily if I have followed my goals.
Acceptance Criteria:
The functionality must be available in the main interface.
The user must be able to undo the action if necessary.
The system must confirm the action with a message afterward.
All data must be saved correctly and remain accessible afterward.

* I am unable to undo the action can you add the posibility of undo the completition of the habit?

* I want you to add in mark-completed and addCompliance pages a Menu button that, when clicked, redirects the user to the main page

### User story 3

* Modify the code such that the habits added in mark-completed are saved in a calendar-like local storage. Then, create a separate html named calendar to implement this third user story: As a user, I want to see a compliance calendar to visualize my progress.
Acceptance Criteria:
 The functionality must be available in the main interface.
 The user must be able to undo the action if necessary.
 The system must confirm the action with a message afterward.
 All data must be saved correctly and remain accessible afterward.

* Erase this message: Green days: at least one habit completed. Blue border: today. --> I want you to include the option for thr user to click on the specific day and show a display of the habits done

* I want you to improve the visual display of the habits when the user clicks. Do a list with button blue and names black.

### User story 4

* Create a separate html named deleteHabits that implements this third functionality: As a user, I want to delete old habits to keep only the relevant ones.
Acceptance Criteria:
 The functionality must be available in the main interface.
 The user must be able to undo the action if necessary.
 The system must confirm the action with a message afterward.
 All data must be saved correctly and remain accessible afterward.

## Screenshots of the final product
![image](https://github.com/user-attachments/assets/e3b8713a-8736-42ba-8e98-c3660ec0607d)

![image](https://github.com/user-attachments/assets/daac7167-dbf0-4bac-897c-6ed58c39e23b)

![image](https://github.com/user-attachments/assets/2da6455a-c70f-470f-93ed-4f8b84c9eda0)

![image](https://github.com/user-attachments/assets/366835a2-97e2-4f08-a112-256950841d37)

![image](https://github.com/user-attachments/assets/454101e2-062e-4ca4-8a91-4cbd81b72893)

![image](https://github.com/user-attachments/assets/01dfaebc-85e3-4646-9532-c91309d94fd7)

![image](https://github.com/user-attachments/assets/2ff49762-5871-40aa-b704-40941e2897bb)


## Lessons learned on the use of Copilot

Using GitHub Copilot in Visual Studio Code has helped us understand both how useful it can be and where its limitations are. Overall, we were surprised by how much it can assist when you give it clear instructions. If you know how to explain what you want, Copilot suggests code that can save you a lot of time and make your work easier.

That said, we also saw that it can’t do everything. For example, we asked it to create a .csv file to store habit data, but that’s when we realized it struggles with more specific or complex tasks on its own. In the end, we simply saved it in local storage.

While working on the project, we each tried to complete the same user stories individually using Copilot. In the end, we compared the results and chose the best version. Interestingly, the outputs varied quite a bit from person to person, depending on how each of us wrote the prompts and other small factors, so there was a bit of randomness involved in which result turned out better.

In conclusion, Copilot isn’t a magical tool, but when used properly, it’s a great support. It helped us be more clear with our ideas and made us realize that communicating well with the tool makes a big difference in the results it gives.

### Git Hub respository: 
https://github.com/sunflower2732/LLM_LAB.git
