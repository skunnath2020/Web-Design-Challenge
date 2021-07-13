# Web Design - Web Visualization Dashboard (Latitude)

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

![Images/landing-large.PNG](Images/landing-large.PNG)


## Latitude - Latitude Analysis Dashboard with Attitude

For this project we'll be creating a visualization dashboard website using visualizations created previously. Specifically plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website must consist of 7 pages total, including:

* A [landing page](#LandingPage) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparison-pages) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A [Images/data-large.png](Images/data-large.png) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

### Considerations

* Use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively,  use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* Bootstrap is recommended. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* Use a CSS media query for the navigation menu.
* Be sure the website works at all window widths/sizes.
* Keep the core functionality the same.

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### <a id="landing-page"></a>Landing page

Large screen:<br>

![Landing page large screen](Images/landingResize.PNG)

Small screen:<br>

![Landing page small screen](Images/landing-small.PNG)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](Images/comparison-large.PNG)

Small screen:

![comparison page small screen](Images/comparison-small.png)

#### <a id="data-page"></a>Data page

Large screen:<br>

![data page large screen](Images/data-large.PNG)


Small screen:<br>

![data page small screen](Images/data-small.PNG)

#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:<br>

![visualize page large screen](Images/visualize-lg.PNG)

Small screen:<br>

![visualize page small screen](Images/visualize-sm.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:<br>
![nav menu large screen](Images/navigation-large.PNG)

Small screen:<br>
![nav menu small screen](Images/navigation-small.PNG)

