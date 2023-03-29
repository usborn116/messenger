# README

This app is just testing out Websocket/Actioncable and practicing creating a messaging app where new messages by users are instantaneously populated into the chatroom, assuming you are logged in.

Tutorial for this was found here: https://github.com/TheOdinProject/curriculum/blob/main/ruby_on_rails/mailers_advanced_topics/actioncable_lesson.md

Some things I did differently were changing the adapter for the development environment in the config/cable.yml file (default was using Redis), as well as adding a stimulus controller to clear the input field for new messages after the new message was submitted. I also changed the positioning of new messages so that they would show up at the top of the view rather than the bottom.