# Project Music Store Analysis
SQL project to analyze online music store data

<b>Project Objective:</b>

The objective of this Music Store Data Analysis project is to gain insights into customer behavior, sales patterns, and inventory management within the music store. By analyzing various datasets including sales records, customer demographics, and inventory data, the project aims to identify trends, correlations, and opportunities for optimization. The analysis will focus on key metrics such as sales performance by product category, customer segmentation based on purchasing behavior, popular items, seasonal trends, and inventory turnover rates. Ultimately, the goal is to provide actionable recommendations to enhance the store's operations, improve customer satisfaction, and maximize revenue.


<h4>Database and Tools</h4>
<ul>
<li>Postgre SQL</li>
<li>PgAdmin4</li>
</ul>

<h4>Schema- Music Store Database</h4>
<img src="https://github.com/rahulsatpathi1997/Project-Music-Store-Data-Analysis/blob/main/MusicDatabaseSchema.png">

<h3>Business Problems</h3>
<p>We have identified some problems by understanding the business</p>
<ol>
  <li>Who is the senior most employee based on job title?</li>
  <li>Which countries have the most Invoices?</li>
  <li>What are top 3 values of total invoice?</li>
  <li>Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. 
Write a query that returns one city that has the highest sum of invoice totals. 
Return both the city name & sum of all invoice totals</li>
  <li>Who is the best customer? The customer who has spent the most money will be declared the best customer. 
Write a query that returns the person who has spent the most money.</li>
<li>Write query to return the email, first name, last name, & Genre of all Rock Music listeners. 
Return your list ordered alphabetically by email starting with A.</li>
  <li>Let's invite the artists who have written the most rock music in our dataset. 
Write a query that returns the Artist name and total track count of the top 10 rock bands.</li>
  <li>Return all the track names that have a song length longer than the average song length. 
Return the Name and Milliseconds for each track. Order by the song length with the longest songs listed first.</li>
  <li> Find how much amount spent by each customer on artists? Write a query to return customer name, artist name and total spent</li>
  <p> Steps to Solve: First, find which artist has earned the most according to the InvoiceLines. Now use this artist to find 
which customer spent the most on this artist. For this query, you will need to use the Invoice, InvoiceLine, Track, Customer, 
Album, and Artist tables. Note, this one is tricky because the Total spent in the Invoice table might not be on a single product, 
so you need to use the InvoiceLine table to find out how many of each product was purchased, and then multiply this by the price
for each artist.</p>
  <li>We want to find out the most popular music Genre for each country. We determine the most popular genre as the genre 
with the highest amount of purchases. Write a query that returns each country along with the top Genre. For countries where 
the maximum number of purchases is shared return all Genres. </li>
  <li> Write a query that determines the customer that has spent the most on music for each country. 
Write a query that returns the country along with the top customer and how much they spent. 
For countries where the top amount spent is shared, provide all customers who spent this amount. </li>
</ol>

