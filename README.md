# Intelligent_Agriculture_Crop-Collection_Robot

## Summary
* The demo uses ROS1, Google Media Pipe with a custom LSTM based NN to perform crop collection in agriculture fields.
* The implemented demo has multiple elemnets from both robotics and AI.
* Original work done in free time.
* The LSTM model for action recognition ( Picking  Fruit / Not Picking)  was trained on custom dataset created using real footage from agtocutural fields( private dataset) and preprocessing it with yolo and media pipe.

## Demo Concept
* Step 1: Pickers of a fruit/ vegeitable would pick the items and collect them in small handheld containers.
* Step 2: The The autonomos mobile robot will use the built in RGB-D camera to track and detect the action being performed by the pickers
* Step 3: When a picker stays still, facing the robot for more than 5 seconds, the robot will automatically detect that, identify the location of the picker and go to the picker.
* Step 4: Once the robot reaches the picker's location, the picker can unload the collected items to the robot's larger carriage box and continue picking.
* Step 5: The robot will move to other pickers and repeat the same untill the carriage is full.
* Step 6: The robot will move to the collection center located at a pre-defined position
* STep 7: The whole process repeats.

## Architecture

  ![drawings_robotics](https://github.com/nirmalka94/Intelligent_Agriculture_Crop-Collection_Robot/assets/111562774/db8389fb-3f1a-4b89-8819-2aa7ed05c964)

## Frameworks
ROS Noetic, Gazebo (Clearpath Husky Simulator), Yolo V5, Gopgle Mediapipe, Pytorch
 <br><i>( Code and other steps to recreate would be added later)</i>
 

 ## Sample Results
 find the demo video here: [DEMO](https://youtu.be/7H6ioa3TKTQ )

