# instant-messaging-app
`COMP3015 - Data Communications and Networking - Project - 2022-23`

## Scenario
A company wants to have a user-friendly WhatsApp/WeChat-like instant messaging app for
internal quick message exchange and file sharing. For security reason, this company wants to
have their own messaging system instead of using the 3th party system.

## Requirements
You need to form a 3-member group and develop a system that meets the company's needs.

```
1. You need to use JAVA SE 1.8 to complete the development.

2. The system operates in a client-server mode. It has two parts:
   a. Client program: It is a desktop application that provides message input and
   display, file upload and download, etc. It works like WhatsApp and WeChat
   message section.
   b. Server program: It handles user login, message exchange and file transmission.
   
3. The client program is a GUI desktop app.

4. The client program requires the user login to operate. User account information is
   stored in the server program.
   
5. The client program allows the user to create/open a chat room if the user wants to
   send an message to another. For example:
   a. Alice wants to send a message to Bob. She needs to create a chat room by
   selecting/entering Bob's name/ID. Then she can send a message to Bob. Bob's
   replies also appear in the chat room.
   b. If there is a chat room with Bob’s talking, no new chat room will be created.
   An existing chat room will open.

6. The client program provides a list of chat rooms. When a user clicks on one of the chat
   rooms, he/she can view the conversation with a specific person.
   
7. When the user sends a message, the message is delivered from the sender’s client
   program to the server program. It will then be transmitted to the receiver's client
   program.
   
8. If the receiver is offline, the message will be stored on the server side until the receiver
   is online. If the receiver comes back online, the stored messages will be downloaded
   to the receiver's client program. The messages stored on the server program will then
   be deleted.
   
9. Users can send files.
   a. If the receiver is offline, the files will be stored on the server side.
   b. If the receiver is online, image files will be transferred immediately, and the
   delivered images will be displayed immediately.
   c. Other files are not transferred immediately even if the receiver is online.
   Instead, the files will be stored on the server side, and specific indicators (e.g.,
   labels with text) will be displayed on the receiver's client program. The receiver
   clicks the indicator to download the file.
   
10. The client program allows the sender to create a chat room with multiple receivers
    (group chat room). 
```