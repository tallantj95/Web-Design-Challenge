# Web-Design-Challenge

<img width="1435" alt="Screenshot 2022-12-14 at 3 19 50 PM" src="https://user-images.githubusercontent.com/112406455/207717850-6968fe97-2cd5-48b7-ae76-215f044994f9.png">

## Background
Data becomes more powerful when you share it with others! That’s because people can use your data only if they can access it. So, you’ll use HTML and CSS to create a dashboard featuring the Latitude vs. X analysis of weather.
## Website
* Here is a link to the website: https://tallantj95.github.io/Web-Design-Challenge/index.html
## Instructions
Create a website by using either the visualizations that you created for your Python-APIs Challenge or the weather data and images that are provided for this Challenge. To do so, use the considerations and website requirements that the following subsections describe.
## Considerations
* Be aware that you must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the Bootstrap grid for responsiveness on the comparison page, and the Bootstrap `table` component for the data page.

* Be aware that you must deploy your website to GitHub Pages, and that as a result, the website must work at a live, publicly accessible URL.

* Make sure to use a CSS media query that uses Bootstrap and/or `@media` for the navigation bar.

* Make sure that your website works at all window widths.

* Feel free to take some liberties with the visual aspects, but keep the core functionality the same as the instructions describe. (For example, keep the comparison visualizations on the comparison page.)
## Website Requirements
The overall requirements for your website are as follows:
* Your website must consist of seven pages.

* At the top of every page, your website must have a navigation bar.

* Your website must be deployed to GitHub Pages.

Next, we’ll describe these requirements in detail.

Your website must consist of seven pages as follows:

* A [landing page](https://tallantj95.github.io/Web-Design-Challenge/index.html) that contains the following elements:

  * An explanation of the project.

  * A link to each visualization page. For these, a sidebar should contain a preview image of each visualization. Clicking an image should take the user to that visualization.

* Four [visualization pages](https://tallantj95.github.io/Web-Design-Challenge/visualizations/temp.html), stored in the `visualizations` folder, each with the following elements:

  * A descriptive title and a heading tag.

  * The visualization for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images that these pages display should be stored in the `assets/images` folder.

  * A paragraph describing the visualization and its significance.

* A [comparisons page](https://tallantj95.github.io/Web-Design-Challenge/comparison.html) that does the following:

  * Contains all the visualizations on the same page so that people can easily compare them.

  * Uses a Bootstrap grid for the visualizations. This grid must contain two visualizations across a medium or large screen and one visualization across an extra-small or small screen.

* A [data page](https://tallantj95.github.io/Web-Design-Challenge/data.html) that displays a responsive table containing the data that the visualizations use, as follows:

  * The table must be a Bootstrap `table` component.

  * The data must come from either exporting or converting the CSV file to HTML. To do so, try using a tool that you already know: Pandas. Pandas has a `to_html` method that generates an HTML table from a Pandas DataFrame.

At the top of every page, your website must have a navigation bar that does the following:

* Contains the name of the site on the left side of the navigation bar, allowing users to return to the landing page from any page.

* Contains a drop-down menu, named Plots, on the right side of the navigation bar that contains a link to each visualization page.

* Provides two more text links on the right side: Comparisons, which links to the comparisons page, and Data, which links to the data page.

* Is responsive (via media queries).

Your website must be deployed to GitHub Pages:

* As a result, the website must work at a live, publicly accessible URL. Save this URL for your later submission.

## File Organization and Structure
* Located in the parent directory are the [index.html](https://github.com/tallantj95/Web-Design-Challenge/blob/main/index.html), [comparison.html](https://github.com/tallantj95/Web-Design-Challenge/blob/main/comparison.html), and [data.html](https://github.com/tallantj95/Web-Design-Challenge/blob/main/data.html) files.
* A [visualizations](https://github.com/tallantj95/Web-Design-Challenge/tree/main/visualizations) folder with the [cloudiness.html](https://github.com/tallantj95/Web-Design-Challenge/blob/main/visualizations/cloudiness.html), [humidity.html](https://github.com/tallantj95/Web-Design-Challenge/blob/main/visualizations/humidity.html), [temp.html](https://github.com/tallantj95/Web-Design-Challenge/blob/main/visualizations/temp.html), and [wind.html](https://github.com/tallantj95/Web-Design-Challenge/blob/main/visualizations/wind.html) stored within. 
* An [assets](https://github.com/tallantj95/Web-Design-Challenge/tree/main/assets) folder that contains the [css](https://github.com/tallantj95/Web-Design-Challenge/tree/main/assets/css) and [images](https://github.com/tallantj95/Web-Design-Challenge/tree/main/assets/images) folders.
* A [Resources](https://github.com/tallantj95/Web-Design-Challenge/tree/main/Resources) folder with the [cities.csv](https://github.com/tallantj95/Web-Design-Challenge/blob/main/Resources/cities.csv), [table.html](https://github.com/tallantj95/Web-Design-Challenge/blob/main/Resources/table.html), and [table.ipynb](https://github.com/tallantj95/Web-Design-Challenge/blob/main/Resources/table.ipynb).


## References
OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/).

© 2022 edX Boot Camps LLC













