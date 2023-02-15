# Animation

  In this mini project we create an App with some animations to look good.
  we crate an app with navigation bar...In this we have logo of our app and App name and some features of app and lgoin, download buttons.
  And then we give some css styles for those..
  
      nav{
          padding: 10px 0;
          display: flex;
          align-items: center;
          justify-content: space-between;
          }.
      logo{
         width:60px;
          }
      
  And then we give styles to list items like text-decoration,color,font-size like this...
  
  
      nav ul li{
                display:inline-block;
                list-style:none;
                margin:10px 15px;
                
            
   Afeter that we give text-decoratio:none,color: to list items..
   Then we add a heading to our and and some paragraph for quick description of our App, a button and add an image.
   After that we give some styles to them like..
   
   
   
        .content{
                 margin-top:10%;
                 max-width:600px;
                }
                
                
                
                
    For heading we give font-size and color,for paragraph we add margin,color,font-size..
    And  for button padding,font-size...
    
    Then we add some aninamion to what we want to goodlook for our app
    
    
    
    
        nav ul li a:hover{
                       text-decoration: underline;
                        color:brown;
                        }->For this when we hover over the list item they will change their text-decoration and color
        .login:hover{
                    text-decoration: underline;
                    color:green;
                    }->in this also we change text-decoration and color
        .btn:hover{
                   border-top-right-radius: 30px;
                  }->for the buttton we change the border-radius to look different
                  
                  
                  
         
    After all this the main animation of app we can add to those we wants to change..like buttons, heading,paragraph and image
    
    
    
          
          .anim{
                opacity: 0;
                transform: translateY(30px);
                animation: moveup 0.5s linear forwards;
                }
           @keyframes moveup{
              100%{
                  opacity:1;
                  transform: translateY(0px);
                  }
                }
                
                
                
    
    And then we add some animation delay to all the items to look some differently for one to another..
    
    
    
    
          animation-delay:0.5s;-->for paragraph
          animation-delay:1s;-->for buttons
          animation-delay:1.5s;-->for image
          
          
          
          
   
    Like this we add some animations to our App 
         
                   
    
