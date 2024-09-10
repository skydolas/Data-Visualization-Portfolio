## General govt. debt OECD

### Part 1
![/OECD-govt debt 2022.png]
<a rel="noopener noreferrer" href="https://data-viewer.oecd.org?chartId=dbe15a84-e68a-4782-bbda-0bd7b8d2367d" target="_blank">Click to interact</a>


### Part 2
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tableau Visualization</title>
</head>
<body>
    <div class='tableauPlaceholder' id='viz1725812534311' style='position: relative'>
        <noscript>
            <a href='#'>
                <img alt='Govt Debt 1995 - 2019' src='https://public.tableau.com/static/images/Go/GovtDebt1995-2019/GovtDebt1995-/1_rss.png' style='border: none' />
            </a>
        </noscript>
        <object class='tableauViz' style='display:none;'>
            <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
            <param name='embed_code_version' value='3' />
            <param name='site_root' value='' />
            <param name='name' value='GovtDebt1995-2019/GovtDebt1995-' />
            <param name='tabs' value='no' />
            <param name='toolbar' value='yes' />
            <param name='static_image' value='https://public.tableau.com/static/images/Go/GovtDebt1995-2019/GovtDebt1995-/1.png' />
            <param name='animate_transition' value='yes' />
            <param name='display_static_image' value='yes' />
            <param name='display_spinner' value='yes' />
            <param name='display_overlay' value='yes' />
            <param name='display_count' value='yes' />
            <param name='language' value='en-US' />
            <param name='filter' value='publish=yes' />
        </object>
    </div>
    <script type='text/javascript'>
        var divElement = document.getElementById('viz1725812534311');
        var vizElement = divElement.getElementsByTagName('object')[0];
        vizElement.style.width='100%';
        vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
        var scriptElement = document.createElement('script');
        scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
        vizElement.parentNode.insertBefore(scriptElement, vizElement);
    </script>
</body>
</html>


### Part 3
<div class='tableauPlaceholder' id='viz1725836743572' style='position: relative; width: 100%;'>
  <noscript>
    <a href='#'>
      <img alt='Germany and Australia Boast Debt Below GDP for Two Decades (The following countries are among the top 10 economies in the world as of 2018)' 
           src='https://public.tableau.com/static/images/De/Debt-less-than-GDP/DebtGDP/1_rss.png' 
           style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='width: 100%; height: 500px; display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='Debt-less-than-GDP/DebtGDP' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/De/Debt-less-than-GDP/DebtGDP/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('viz1725836743572');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';

  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


The following line chart represents the debt as percentage of GDP between 1998-2018 for top 8 countries in OECD. These countries are also among the top 10 world economies. The line chart focuses on how over the two decades Germany and Australia have maintained their debt percentage below GDP, whereas the other countries have failed to do so. In order to create this focus I have chosen 100% as a threshold line. Countries having GDP above 100% in 2018 are set in background using grey. Additionally Germany and Australia has been shown in two distinct colors to show distinction and create focus. Using interactive functionality of Tableau, hover feature is used to display specific details for each country. A bold descriptory title is used to build context and make the the data visualization more comprehensible.

### Summary
The 3 visualizations bar chart, heatmap, line chart showcase different stories, even though they use same data in the backend. 
Bar chart is focused on showing the debt as percentage of GDP for all OECD countries in 2022. To draw attention to what's happening with top 3 countries Japan, United States and Germany are highlighted.
Heat map focuses on showing how different countires have handled debt from 1995 to 2019. It does so by having 100% as the center value and using color gradation to represent highs and lows in orange and blue. Blue being debt < 100% of GDP and red being debt>100% of GDP. The concept of heat map helps in getting a nice comparative overview.This map unlike bar chart shows the density of debt across time and countries.
Line chart on the other hand uses a subset of data to dsiplay how two countries of the top 10 economies have maintained their debt percentage below 100 for 2 decades (1998-2018). This chart unlike other shows trend over the years.
