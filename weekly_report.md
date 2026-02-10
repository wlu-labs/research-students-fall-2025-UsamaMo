## Weekly Report
- This file contains a paragraph of 1000 Characters or more about the progress made by the student for each week. I am creating the place holder for it.

### Week 1 (Date:  Aug 31 - Sept 6)
- Had a meeting with professor Sukhjit regarding multiple projects and the VLN project
- Discussed the various technical issues I had with the robot previously in my other research

### Week 2 (Date:  Sept 7 - Sept 13)
- Got everything setup with the course
- Filled out the course override form for CP494 Directed Research Studies II
- Filled out the consent form
- Got familiar with the research notion page, guidelines
- Attended both meetings on Wednesday and Friday
- Started reading research papers

### Week 3 (Date: Sept 14 - Sept 20)
- Updated Literature Review table with literature review from 4 research papers
- Added all research papers to Zotero
- Thoroughly analyzing each research paper trying to understand the different localization and mapping algorithms such as SLAM and EFK and for different types of machines these algorithms were used on

### Week 4 (Date: Sept 21 - Sept 27)
- Kept reading research papers more in depth
- Knowledge transfer with Bantu and had some explanation on the general overview of this project and its architecture
- Asked Sherry for more research papers on Path Planning Algorithms

### Week 5 (Date:  Sept 28 - Oct 4)
- Bantu left for vacation attaching perception model output and perception model ipynb
- I tried connecting the findings in the research papers, trying to understand R2R Dataset given the R2R powerpoint by sherry
- Showcased my robot on Fridays meeting and also how to remote into the robot using rustDesk

### Week 6 (Date: Oct 5 - 11)
- Started working on the python code implementation on the robot
- Trying to take the perception model  as a python notebook, converting it to a python file and running it in the robot, including downloading datasets on the robot.
- Unfortunately as I was updating the OS to match the dependencies in the python file, using sudo apt update and sudo apt upgrade and that ended up crashing the entire OS.

### Week 7 (Date: Oct 5 - 11) -> Reading Week

### Week 8 (Date: Oct 19 - 25)
- Meeting with Bantu regarding the implementation on the robot and the errors I was facing
- Got recommended to start focusing more on the path planning and localization as that was more of a priority
- Unfortunately as I was updating the OS to match the dependencies in the python file to get it working on the robot, using sudo apt update and sudo apt upgrade and that ended up crashing the entire OS.
- Spent many hours trying to reflash the OS onto the Jetson Orin NX and have documented everything so far on a google sheet

### Week 9 (Date: Oct 26 - Nov 1) 
- Sucessfully reflashed the Jetson Orin NX using Jetpack 5.13 and using installer image for the Jetson Orin NX 16GB
- Tested various functionalities on the robot to see if everything was fine
- For more computational power, Yahboom support recommended the Jetson Orin NX Super Mode. Downloaded the Installer Image on my Windows Laptop and installed a Ubuntu 22.04 upgraded version on my windows laptop. Partitioning the SSD using Disk Genius and flashing the Jetson Orin NX using the jetpack in the VM.
- Meeting with Bantu and Hamad discussing going forward.
- Bantu shared Connectivity files and guided me on how to create the path planning model using the view points, Map GPT and connectivity files.
- Started working on the path planning code which included:
    - using connectivity files to graph and map the connected view points
    - using a start view point and goal viewpoint, map a connected path between nodes
    - find the coordinates of the nodes
    - output these findings to a json file

### Week 10 (Date: Nov 2 - Nov 8)




