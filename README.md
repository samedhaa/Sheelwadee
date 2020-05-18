Google-docs-backed-blog-platform  
  
    
      
Our idea:  
We want to make a blog platform similar to medium.com but uses Google Docs API for writing articles (optional main feature)  
  
Similar projects:  
https://github.com/gkiely/ydnw (we basically need to make an app similar to this app but better)  
  
Helpful packages:  
https://github.com/pennersr/django-allauth  
https://github.com/nesdis/djongo  
  
  
Features:  
 1.Register as a user and hook Gmail account  
   
 2.View other people blogs and articles and see the most popular blogs  
   
 3.Adding Articles to user blog and using a google document  
   
 4.Programmatically add Trigger on user google document save to send a request us to check for changes and update the document 
   
 5.User “admin” panel where they can manage added articles and check reactions and traffic on their blog, and be able to delete/publish/add new articles to their blogs.   
 
   
   
     
       
Suggested Technologies:  
Django as the main web framework (has good SEO built-in)  
Use PostgreSQL for the user and Gmail auth, and use MongoDB for article and blog data storage, look into using firebase as article storage  
Use https://editorjs.io/ as an alternative to Google Doc editing  
  
