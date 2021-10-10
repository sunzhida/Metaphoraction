## Welcome to GitHub Pages

![](images/interface.jpg)


1. This repository contains the following contents:
    1. README.pdf: a brief introduction of Metaphoraction
    2. requirements.txt: the project dependencies are listed in this file
    3. run.py: the file used to start the server
    4. database.db: the database to store the design pathways
    5. app: the frontend and the server of Metaphoraction
    6. [P1]_dependencies_setting_guideline.pdf: a brief instruction on how to set up the environment for Metaphoraction

2. Set up python environment on your local computer: Please follow (f) if you have not installed python environment (>=3.6) in your local machine; if you have already deployed python environment (>=3.6), you can simply install project dependencies by typing the following command under the project path ./metaphoraction:

```bash
$pip install -r requirements.txt
```


3. Download the WordNet dataset: After installing all the required packages, you still need one more step to install the WordNet dataset if you never used the dataset before.

```python
 >>> import nltk
 >>> nltk.download('wordnet')
```


4. Experience Metaphoraction: After installing all the dependencies, please go to the ./metaphoraction and start the server by

```bash
$python app.py
```

If everything is OK, you will see that the app is running on `http://0.0.0.0:5000/`
Then you can type the link `http://127.0.0.1:5000/` to your local web browser (Chrome recommended) to explore Metaphoraction.

5. Keep the log files: There are two files which are used to track your operating records on how you used this tool.
We logged your mouse click event and stored the data in the *./metaphoraction/clickHistory.txt* and *./metaphoraction/pinHistory.txt.*
Kindly send us these two files after you finished your tasks in this channel (#lab1-metaphoraction).

6. Please feel free to leave comments on your experience when using Metaphoraction or any suggestions to improve this tool.
You are also welcome to contribute your code by modifying or adding functions to Metaphoraction.
Please note that do not spread the code outside the class because this tool is currently under review.

You can use the [editor on GitHub](https://github.com/sunzhida/Metaphoraction/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sunzhida/Metaphoraction/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
