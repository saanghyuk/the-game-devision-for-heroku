<h2>Game_Division_Project</h2>


<pre>
This project has benn deployed on Heroku.
Also, there are seperate git repositories 
(for Heroku Deployed version & local version)  
</pre>

<h4>
<pre>
1. git clone<br><br>
2. npm install<br><br>
3. heroku login<br><br>
4. heroku create<br><br>
</pre>

And then we have to use MongoDB on heroku

<pre>
5. git push heroku<br><br>

6. heroku logs

->this will show the reason why we fails(Maybe Mongo Error)<br><br>

7. heroku addons:create mongolab:sandbox<br><br>
8. heroku config
-> check environment variables<br><br>
9.  heroku config:SET=asdjkflajsdf
(This will addd 'SECRET' environment variable)<br><br>
10. heroku config<br><br>
11. git push heroku master<br><br>
12. heroku open
</pre>

Also you can check your heroku mongolab on heroku website >> resources >> mongolab

<a href="https://github.com/saanghyuk/defi_node/tree/master/12_the_game_division">
Git repository for Local Version
</a>


</h4>
