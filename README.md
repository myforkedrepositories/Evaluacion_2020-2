# Evaluaciones 2020-2
Tareas y Exámenes 2020-1 del curso:

https://github.com/restrepo/ComputationalMethods

# Instructions to make the pull request
## From the GitHub page
* Creates a GitHub account and go to [this repository](https://github.com/ComputationalMethods/Evaluacion_2020-2/)
* Fork this repository to your github account with the button "Fork" in the upper right-part of this web page in GitHub
* In the forked repository  Make a directory with your identification number by creating a file `README.md`. For this, for one idenfication number, let say 6666666, use the button `Add File` → `Creates new File` and in the `Name your file...` field, write `6666666/README.md`. Then go to the end of the page and click on the "Commit new file" green button.
* Tu upload your Homework navigate until the created directory and use the button `Add File` → `Upload file`. Then go to the end of the page and click on the "Commit new file" green button.
* Finally click on the "Pull requests" tab → "New pull request" green button → "Create pull request" green button → Fill the "Title" box and click the "Create pull request" green button. 
* Check that the pull request is effectively created in https://github.com/ComputationalMethods/Evaluacion_2020-2/


## From the command line
* Only the first time: From your forked copy, clone (replace `YOURUSER` with your user name at GitHub or copy from the Clone green button field):
```bash
git clone https://github.com/YOURUSER/Evaluacion2020-1.git
```
After the clone follow the next step
* Update the repository
```
git pull origin master
```
* Change to the repository base
```bash
cd Evaluacion2020-1
```
* Make a directory with your identification number, for example
```bash
mkdir -p 98533678
```
* Go there with
```bash
cd 98533678
```
* Copy the notebook with your homework or examination there, let say: `tarea_01.ipynb` (you can use the Raw download from github with `wget` directly from any working repository). After that, register the new file in the repository with:
```bash
git add tarea_01.ipynb
```
* Register the change in your local repository with a clear messsage with
```bash
git commit -am 'Tarea 01: Jueves 25 de febrero'
```
* Upload the changes to your forked repository in GitHub with (your login information will be requested)
```
git push origin master
```
* From the forked repo in your GitHub account at `https://github.com/YOURUSER/Evaluacion2020-1` with the proper credentials, use the button "New pull request" and follow the green buttons until the end.

# Submodule help
To update the changes from the main repository:
```bash
git submodule update --remote Evaluacion_2020-2
```
