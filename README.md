# Voice Assistant - Tux
## Senior Project - Wartburg College

### Background

I am an Undergraduate student of senior standing at [Wartburg College](https://www.wartburg.edu/) pursuing a degree in Computer Science and Actuarial Science. For my senior project, I wanted to research and puruse machine learning, and get to learn what various techniques are implemented to make a voice assistant work. After being introduced by Dr. John Zelle, and along with some research, I found [MycroftAI](https://mycroft.ai/)'s team that provided the [tools](https://github.com/MycroftAI) that I could use to create my own voice assistant. 

This is completely a research-based project since I had litlle knowledge of machine learning, and no knowledge of the tools provided by MycroftAI. Thus, as I learn along, this page will provide further information regarding the things I have achieved thus far. 

I will utilize version control for this project because I might need to make some adjustments to the code provided by the MycroftAI's team in their repository(repo), and it will also serve as a way for me to document my work. Thus I am planning on using Git and also GitHub since I want to show the progress I've made.

### Git

The first thing I did was install git on my machine. 

```markdown
sudo apt update
sudo apt install git
```

Then I cloned the MycroftAI's [mycroft-precise repository](https://github.com/MycroftAI/mycroft-precise) and initiated my local git repo within that folder.

```markdown
git clone https://github.com/MycroftAI/mycroft-precise
git init
git add .
git commit -m "<comment>"
```

I have created a [Git cheat-sheet](https://docs.google.com/document/d/1N3ToWxiGmmR6QWdNF1TplYEpfsYLyMqc2AeIdb_Q4dg/edit?usp=sharing) so that I have quick access to all the commands that I will need. This has been made possible due to the people that have been linked to within the cheat-sheet. Although it has helped me quite a lot, I would recommend that you understand what the commands do before you start typing them up just to be on the safe side.

### GitHub

The second step to my project was to create a GitHub account. This is because I want to show the progress to anyone who would like to see. As I begin to learn more and more about this platform, I am adding my information on a [Google doc](https://docs.google.com/document/d/1N3ToWxiGmmR6QWdNF1TplYEpfsYLyMqc2AeIdb_Q4dg/edit?usp=sharing) that helps me easily revisit all of the things I've learned about GitHub.

After creating my project folder on GitHub, I pushed my local repo onto the online one, but before doing that I created a readme markdown file for my project with the following commands.

```markdown
echo "# CS-460-Project" >> README.md
git add .
git commit -m "<comment>"

git remote add origin <URL>
git push -u origin master
```

This created my markdown readme file and also linked my local repo to [my online GitHub acccount](https://github.com/shahzeb-jadoon/CS-460-Project).

### mycroft-precise

### DeepSpeech

You can use the [editor on GitHub](https://github.com/shahzeb-jadoon/CS-460-Project/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repo, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/shahzeb-jadoon/mycroft-project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

