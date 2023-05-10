# Pegasus WMS USC Tutorial

This repository contains preconfigured Pegasus Workflows examples including the Pegasus Tutorial, to run on USC CARC Discovery Cluster resources. 

## Getting Started
To get started, use a web browser and log on to USC OnDemand Instance at https://ondemand.carc.usc.edu . You need to be on USC Network and need to your USC credentials to log in. More details on how to logon to USC Open OnDemand can be found at https://www.carc.usc.edu/user-information/user-guides/hpc-basics/getting-started-ondemand

To start a Jupyter notebook server, Click on Interactive Apps and then select JupyterLab

![Start JupyterLab](./images/jupyterlab-start.png)

When launching the Jupyter Lab, it is important to select the following
* For Cluster specify Discovery
* For Account specify the account you normally use like ttrojan_123
* For Partition specify htcondor

The above are important to ensure you start a JupyterLab Server on a node, that has HTCondor installed and preconfigured to submit your workflows

![Launch JupyterLab](./images/jupyterlab-launch.png)

Once your JupyterLab Session starts, Click Connect to JupyterLab button

![Connect to Running JupyterLab](./images/jupyterlab-running.png)

From there, Click on File -> New and then click on Terminal to get the terminal

![Shell Access In Jupyter](./images/terminal-start.png)

Once in the terminal clone this GitHub Repository

```
$ git clone https://github.com/pegasus-isi/pegasus-usc-tutorial.git
```

In Jupyter, navigate to the example you are interested in, and step through the notebook. Once the workflow is submitted, you have to add compute resources with HTCondor Annex.

For first time users, we highly recommend to do the notebooks in order, as they build up on concepts in the previous notebooks.

