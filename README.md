# nr1-plotly

## Custom Visualization

1. Download and install nr1-cli and npm
2. Run `nr1 create --type visualization --name barchart` and name the nerdpack `nr1-plotly`
3. Change to nerdpack directory: `cd nr1-plotly`
4. Create more custom visualizations:
```
nr1 create --type visualization --name boxchart
nr1 create --type visualization --name displot
nr1 create --type visualization --name heatmap
nr1 create --type visualization --name bubblechart
nr1 create --type visualization --name histogram
nr1 create --type visualization --name linechart
nr1 create --type visualization --name scatterplot
```


## Getting started

1. Run `nr1 nerdpack:serve` and get links in the output console.
2. In New Relic (local), go to Apps > Custom visualizations to see the charts

3.  If that doesn't work, try to run the following scripts:

```
npm install
npm start
```

Visit https://one.newrelic.com/?nerdpacks=local and click on Apps > Customvisualizations

## Creating new visualizations

If you want to create new artifacts run the following command:

```
nr1 create --type visualization --name anotherchart
```
