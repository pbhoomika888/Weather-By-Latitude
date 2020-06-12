# Weather By Latitude

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

![Images/landingResize.png](Resources/assets/images/landingResize.png)


## Latitude - Latitude Analysis Dashboard with Attitude

Created visualization dashboard website using visualizations. 

In building this dashboard, I created individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. I created have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements



* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).



### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

#### Landing page

Large screen:
![Landing page large screen](Resources/assets/images/landing-lg.png)

Small screen:
![Landing page small screen](Resources/assets/images/landing-sm.png)
￼

#### Comparisons page

Large screen:
![comparison page large screen](Resources/assets/images/comparison-lg.png)

Small screen:
![comparison page small screen](Resources/assets/images/comparison-sm.png)

#### Data page

Large screen:
![data page large screen](Resources/assets/images/data-lg.png)

Small screen:
![data page small screen](Resources/assets/images/data-sm.png)

#### Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:
![visualize page large screen](Resources/assets/images/visualize-lg.png)

Small screen:
![visualize page small screen](Resources/assets/images/visualize-sm.png)

#### Navigation menu

Large screen:
![nav menu large screen](Resources/assets/images/nav-lg.png)

Small screen:
![nav menu small screen](Resources/assets/images/nav-sm.png)

