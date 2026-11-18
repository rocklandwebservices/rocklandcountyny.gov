# rocklandcountyny.gov
Failover page for https://rocklandcountyny.gov/

The pages are built using Jekyll includes to for a more modular method of switching content in and out of the main index page. 

For example, to add an alert to the main page simply duplicate of the alert html files, modify the html to set your message, then include it where you want it to appear using the jekyll include variable {% include myNewAlert.html %}. All files referenced in the include MUST reside in the _includes folder. You can choose to include file fragments relative to the current file by using the include_relative tag:{% include_relative somedir/footer.html%}.

See https://jekyllrb.com/docs/includes/ for more information.
