# c323-project7
# Android remodeled notes app
Dynamic Android Mobile application that functions as a notes app using cards and staggered grid  layout

## Functionality 

The following **required** functionality is completed:
 
* [x] Application uses firebase realtime database
* [x] user stores notes within separate screen take advantage of recycler view
* [x] Information is maintained on realtime database
* [x] Takes advantage of valueEventListener to update only on change instead of updating the whole list
* [x] Notes should change and state maintained on any device 


## Video Walkthrough

Here's a walkthrough of implemented user stories:

![]().

## Notes

This project takes advantage of the Firebase Realtime database by storing the information in cloud DB. This allows user to login from any device and access the same information. Information is represented within notescreens which are made up of recyclerViews. Information is updated only when an event triggers such a change

## License

    Copyright [2023] [Samuel Barrido]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
