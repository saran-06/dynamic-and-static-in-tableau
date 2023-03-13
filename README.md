# dynamic-and-static-in-tableau
Hello guys, Today I want to share my work in dynamic and static views in Tableau. Tableau has high Interaction with users because it supports both views(Dynamic and static)
#Static_views:
I have done 1 task in static views.
*Finding the top 11 to 20 customers:
If we want the top 10 customers we can easily go to
filter then you can identify the Top option. You can use that
filter condition to complete the above task. But our goal is
to findTop11 to 20 customers. I have created individual sets
for the top 20 and top 10 and created an inner join. It gives
the top 11 to 20 customers.
#Dynamic_views
I have done 2 tasks in dynamic views.
*Finding latest 3months sales:
I have used a calculated field to complete this task.I
used DATEDIFF and DATETRUNC functions in tableau.
calculation:
DATEDIFF('month',DATETRUNC('month',[Order Date]),
{MAX(DATETRUNC('month',[Order Date]))})<=2
*Finding a set of 10 top customers dynamically:
I have done this task using parameters in tableau.
We can create a parameter and pass the values to it.
link:https://lnkd.in/gA9DarVd
