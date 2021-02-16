## COSC432 Final Project ##

#### Development Instructions ####



###### Installing Anaconda ######
- Follow the instructions to download Anaconda at [Anaconda.com](https://www.anaconda.com/)
- If you are using a mac for development this may be easier [Here](https://mas-dse.github.io/startup/anaconda-macosx-install/)
- During download you may be asked if you want to **Initialize Anacoda3 by running conda init**, choose *yes*
- To verify it has been installed correctly run `conda --version` you should see `conda 4.7.10`


###### Running A Jupyter Notebook ######
Anaconda3 will come preinstalled with conda, pands, numby, jupyter and a bunch of other tools.

- Make a directory in your terminal and `cd` into it
- Run the command `jupyter notebook` from inside the directory
    - This will spin up and open a blank jupyter notebook on port 8888
    - Running `jupyter notebook` in a directory will essentially "wrap" whatever the contents of that directory are into a notebook and spin it up

###### Initializing this Repository to Contain your Notebook ######
- Navigate to the directory where you ran your your jupyter note book and run the following `git clone https://gitlab.com/wjdingman1/cosc-432.git`
- You should now have a **cosc-432** directory which will serve as your local repository of everything from this project
- For consistency, always spin up the notebook from the **cosc-432** directory so we are not modifying our paths when committing

