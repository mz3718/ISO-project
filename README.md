# ISO-project
The Independent Study Option

The project title is "Comparing Vision and Tactile Data to Teach Robots Dexterous Skills using Deep Reinforcement Learning"

Project Description:
Deep Reinforcement Learning is a powerful technique for training robots. For example, a robot could be taught to control a humanoid hand to
perform dexterous tasks, such as rotating an object within the palm of the hand, using the fingers. To train such a controller, the state 
must be defined, which represents the input data used by the controller to output the appropriate commands to the fingers. One example of 
state data would be to use an image of the hand and the object, such that the robot learns how to interpret the image and act accordingly. 
Another example would be to use tactile sensors on the fingertips, such that the robot learns to manipulate an object using tactile data. 

Humans use a combination of these; we use vision for initialising a manipulation task, and then tactile data for fine-grained control. 
However, it is not clear yet what the relative merits of vision and tactile sensing are for robots. In this project, you will investigate 
the relative performance of a controller, trained using deep reinforcement learning, when using vision as its state, compared to when using
tactile data as its state. Experiments will be carried out in simulation using the V-Rep robotics simulator, using a model of a humanoid
robotic hand, on a number of different dexterous manipulation tasks. As an extension, you may investigate different kinds of visual data, 
such as RGB images and depth images, and different kinds of tactile data, such as binary ("touching" or "not touching") or continuous 
("how much pressure") sensors. For advanced students, you may then be able to design your own state representation, which combines both 
vision and tactile data, to benefit from the best of both.
