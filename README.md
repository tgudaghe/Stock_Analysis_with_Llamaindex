# Stock_Analysis_with_Llamaindex

## Step 1: Setup the environment

1. On git hub create repository first
   a. Give name as Stock Analysis using Llamaindex
   b. Copy URL

---

2.  In anaconda terminal or git bash clone the repo.
    a. Navigate to your local directory folder. - Before that run "conda init bash" so that anaconda is integrated with Git bash or use git directly.

        	``` bash
        	conda init bash

        	``` bash
        	clone girhuburl

    I

---

Open VS code open the folder of repository

3. Create virual env

   ````bash
   a. conda create -n stock_analysis python=3.10 -y

   ``` bash # activate conda environment

   b. conda activate stock_analysis
   ````

---

4. Create a requirements.txt file which will list all components and pacakges

5. Create a folder stucutre using template.py file.

6. Create a setup file
   a. To check list of package run below command in bash
   pip list

7. Checkin project files on github.
   a. git add .
   b. git commit -m "folder structure added"
   c. git push origin main

---

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```
---

### STEP 03- Run the application
```bash
# Finally run the following command
streamlit run app.py
```

```bash
Streamlit application should launch in browser with port 8501 or 8502
```
