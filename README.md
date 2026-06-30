# judenken-checker
Judenken Checker

A simple checklist web app for tracking visits to Japan’s Important Preservation Districts for Groups of Traditional Buildings, commonly known as Judenken.

This app displays Judenken districts by region and lets you check off the places you have visited. Your progress, including the number of visited districts and completion rate, is shown at the top of the page.

The checked status is saved in your browser’s local storage, so your progress will remain available when you reopen the page on the same device and browser.

Live Demo

https://shiro354.github.io/judenken-checker/

Features

* List of Judenken districts across Japan
* Region-based grouping
* Visit checklist
* Progress counter
* Completion percentage
* Progress bar
* Automatic progress saving using local storage
* Share progress on X, formerly Twitter

How to Use

1. Open the live demo page.
2. Check the districts you have visited.
3. View your current progress at the top of the page.
4. Use the share button to post your progress on X if you like.

Your progress is saved automatically in your browser.

Data Source

The district data is based on the official list of Important Preservation Districts for Groups of Traditional Buildings published by the Agency for Cultural Affairs, Government of Japan.

* Source: Agency for Cultural Affairs, “Important Preservation Districts for Groups of Traditional Buildings”
* Coverage: Judenken districts across Japan
* Number of districts: 129

Please note that the data may not always reflect the latest official information. New designations, name changes, or other updates may occur, so please refer to the official source when accuracy is required.

Tech Stack

This app is built as a static web page using only HTML, CSS, and JavaScript.

* HTML
* CSS
* JavaScript
* localStorage
* GitHub Pages

No framework or build tool is required.

Running Locally

Clone this repository:

git clone https://github.com/shiro354/judenken-checker.git
cd judenken-checker

Open judenken.html in your browser.

On macOS, you can run:

open index.html

On Windows, you can open the file by double-clicking judenken.html in File Explorer.

File Structure

judenken-checker/
├── README.md
└── index.html

Notes

Progress is saved in the browser’s localStorage.

Because of this, your progress may not be carried over in the following cases:

* You use a different device
* You use a different browser
* You clear your browser data
* You use private browsing or incognito mode

Possible Future Improvements

* Completion rate by region or prefecture
* Filter for unvisited districts
* Search by district name
* Map links for each district
* Export and import progress data
* Easier data maintenance and verification against the official list

License

No license has been specified yet.

If you want others to use, modify, or redistribute this project, consider adding a LICENSE file.

## Privacy

This site uses privacy-friendly analytics with GoatCounter to understand overall usage trends.

Your checklist data is stored only in your browser using localStorage.  
It is not collected, transmitted, or shared with the site owner.
