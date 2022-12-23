# Pagination

## Learning Objectives

How to paginate a dataset with simple page and page_size parameters
How to paginate a dataset with hypermedia metadata
How to paginate in a deletion-resilient manner

## Description 

You can paginate the JSON response that is called from the REST API. The order of the data is retained from page to page.

Given the ability to paginate, you can quickly populate tables and make new REST calls every time you go to the next page of the data on the table. There is significant load time if you want to populate the data table with many rows (greater than 1000) from the Data REST API.