##### Kaggle competitions
- Featured competitions: difficult, high prize
- Research competitions: 
    - More experimental
    - No prizes or points
- Getting-started: easiest, no prizes or points
- Playground: 
    - One step above the Getting Started
    - Trying out a new technique in a lower-skates setting
    - Small prizes
- Recruitment:
    - Uncommon
    - Interested participants can upload their resume for consideration by the host
- Annual: not strict, hosted by Kaggle twice a year.
- Limited-participation: private or invite-only.
- Formats:
    - Simple
    - Two-stage
    - Kernels only
        - More balanced as all the users have the same hardware available.

##### Kaggle datasets
- Csv, json, SQLite, archives, Big Query
- Creating a dataset:
    - Setup automatic internal updates: in case data are updated periodically.
    - Manual setting: dropdown in the data set menu header.
    - Can create a dataset from kernel's output files
    - Create a dataset and update it from one data source only.
    - To use multiple datasets in your Kernels, you need to create upload them seperately.
- Upload:
    - Option to select any organization you're a part of.
    - Dataset Collaboration allows multiple users to own and maintain a private or public dataset.
    - You can make public kernals on a private dataset and vice versa.

##### Kernels
- 2 types:
    - Scripts: files that execute everything in a sequence.
    - Notebooks: Jupiter Notebooks are composed of cells. 
- Kaggle Kernels have become a huge repository of public, open-sources, and reproducible code for Data Science and Machine Learning problems.
- Browsing Kernels tab inside a competition is a good way to get access to all the kernels associated with the specific dataset. 
- Kernel editor: editing window, console, and setting window.
    - Script are more popular for writing code for competition submisstions because of their batch execution nature.
    - Notebooks are popular for Exploratory Data Analysis and for tutorials.
    - Once the kernel is made public, it cannot be made private again. 
- Add data sources to the kernel: 
    - Launch a kernel from within a dataset or a competition.
    - Click the add data button to search for your desired dataset.
    - Can also add kernel output files up to 5GB
- Collaborating on kernels: settings/sharing option.
- Docker Container.
    - Kernel versions are not only limited to your compiled code. They include log files, output files, data sources, and more.
    - By default, the latest version of your kernel will be shown to the users in the kernel viewer. 
    - Another option for installing a package is from a configured GitHub Repository.
        - Command:[account]/[repository]
        - install_github("some_user/some_package")
    - Install custom packages using kernel editor: !pip install my-new-package
        - Upgrade/downgrade an existing package: !pip install my-existing-package==X.Y.Z

