# What is Pandoc?
 
 Pandoc is a free-software document converter,
 widely used as a writing tool and as a basis for publishing workflows.
 If you need to convert files from one markup format into another, 
 pandoc is your swiss-army knife.

 ---

 # Features of pandoc?
 
  1. With the help of this converter you easily convert one markup format to other.
  2. It can also be able to handle mathematics contain latex and convert it into pdf,text or any other format.
  3. For observing the versatility of this converter you can refer [pandoc.org](https://pandoc.org/)

  ---

  # How to install pandoc?
  
  1. Go to pandoc.org .
  2. Click the icon displayed top left named installing .
  3. Choose the type of Operating system( linux, window etc.)
  or you can directly refer this 
  [install pandoc](https://pandoc.org/installing.html)

  ---

  # After installation.
  1. Open a terminal.
  To verify pandoc is installed or not.
  **Use (pandoc --version) command in cmd.**
  
  ---
  
  # Simple conversion commands in command prompt
  
  1. First you can simply write pandoc in cmd.
  2. write a simple text it in html or markdown language.
  3. press ctrl+z in windows or ctrl+d in linux.
  4. press enter.
  5. now see your code changed from one markup language to other.
  sample screenshot
  ![Screenshot (142)](https://user-images.githubusercontent.com/98117962/180228623-239c743b-ff85-4ca1-a7aa-2f4688af1d1a.png)
 This what happen when user does not provide the input and output type of file.
 So, *pandoc* consider **markdown** as input and **html** as output.
 
 ---
 
 # How to specify input and output commands in pandoc
  
  Sample command to convert a file text file to html.
  1. for simple output file 
  pandoc input file -o output file
  **pandoc sangam.html -o sangam.md**
  2. for standalone file
   **pandoc -s -f markdown -t html sangam.md**

   For more information kindly refer [User's Guide](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.694.6340&rep=rep1&type=pdf)
   
   ---
   
   
  # I faced an error during converting different types like html,markdown,docx etc to pdf.
  
    for converting into pdf follow below steps
   1. First you have to install latex. [follow this](https://miktex.org/download)
   2. After installing check pdf engine install in Command prompt with --pdf-engine command.
   3. Check below packages are installed or not . 
   g LaTeX packages are available: amssymb, amsmath, ifxetex,
ifluatex, listings (if the --listings option is used), fancyvrb, longtable, url,
graphicx, hyperref, ulem, babel (if the lang variable is set), fontspec (if xelatex or
lualatex is used as the LaTeX engine), xltxtra and xunicode (if xelatex is used).

---

# Now convert into pdf.
 
 Use command ( pandoc input.extension -o output.pdf)
   
   THANK YOU.. :smile:
