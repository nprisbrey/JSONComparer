# JSONComparer
A webpage that highlights differences between files of type JSON and HAR. A three day project, fit in around work and school, because other online diff utilities wouldn't let me bulk edit the files I was comparing.

## Usage
Open the "comparer.html" file in your webrowser of choice (has been tested in Chrome and Firefox). Using the two "Choose File" buttons, select the two different files you'd like to compare (must be JSON or HAR format). Once selected, click "Load Files" and view the differences!

### Blue Buttons
The blue buttons that appear between the "Choose File" button and the colored comparison are all the keys found in that file. If there is a key you don't want, simply click the corresponding button and all keys with that name in the file will be removed!

### Red "X" Buttons
When an object is hovered over, a red "X" will appear to the left. Clicking the "X" will remove the entire object from the comparison.

### Colors
Green means there's a matching key/value pair found in the other file, Yellow means there's a matching key with a different value in the other file, and Red means there is no corresponding key found in the other file.

### Warnings
There is no sanitization occuring when the files chosen are loaded and displayed! This means that any malicious code you're loading will be run upon clicking the "Load Files" button.

## Examples
### Example 1
This first image is an example of what the page looks like after loading the two example JSON files. The keys for each JSON are shown in the blue buttons.
![image](https://user-images.githubusercontent.com/10404106/226209596-be126960-bfe7-43d1-87d1-a430423b0687.png)

### Example 2
This second image is an example of what the actual comparison looks like and a red "X" button allowing the user to delete an object from one side, which appears upon hovering.
![image](https://user-images.githubusercontent.com/10404106/226209993-87b955e4-c1c2-4811-bc81-b1364025e6df.png)
