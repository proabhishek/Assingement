# Assingement

Link:  https://javascript.info/task/find-elements/table.html 

How to find?…

The table with id="age-table".
All label elements inside that table (there should be 3 of them).
The first td in that table (with the word “Age”).
The form with name="search".
The first input in that form.
The last input in that form.

# SOLUTION:
1)table= document.getElementById("age-table")
 <table id=​"age-table" style=​"user-select:​ auto;​">​<tbody style=​"user-select:​ auto;​">​<tr       style=​"user-select:​ auto;​">​…​</tr>​<tr style=​"user-select:​ auto;​">​…​</tr>​</tbody>​</table>​
2)label = document.querySelector("label")
  <label style=​"user-select:​ auto;​">​"Search the site: "<input type=​"text" name=​"search"           style=​"user-select:​ auto;​">​</label>​
3)firstId = document.getElementsByTagName("td")
  HTMLCollection(4) [td, td#age-list, td, td, age-list: td#age-list]
 3)firstId[0]
  <td style=​"user-select:​ auto;​">​Age:​</td>​
4)form = document.querySelector("form")
  <form name=​"search" style=​"user-select:​ auto;​">​…​</form>​
5)document.querySelector("input")
  <input type=​"text" name=​"search" style=​"user-select:​ auto;​">​
6)document.querySelectorAll("input")
  inputs = document.querySelectorAll("input")
  inputs[1]
  <input type=​"submit" value=​"Search!" style=​"user-select:​ auto;​">​










