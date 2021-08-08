<template>
  <div id="app">

        <h1> TODO LIST APP </h1>
          
            <div id="flex">
                   <input id="text" type="text" placeholder="write what do you want to do ?">

                   <input type="checkbox" class="check">
            </div>
           
           
           <div id="todo">
                
                <div class="todo">
                   
                   <input type="checkbox" class="check">

                    <p>Lorem ipsum dolor sit amet consectetur.</p>
                     <button class="x">x</button>
                </div>
                   <div class="todo">
                   
                   <input type="checkbox" class="check">

                    <p>Lorem ipsum dolor sit amet consectetur.</p>
                     <button class="x">x</button>
                </div>
                 <div class="todo">
                   
                   <input type="checkbox" class="check">

                    <p>Lorem ipsum dolor sit amet consectetur.</p>
                     <button class="x">x</button>
                </div>
                
                <div id="todo-button">

                       <div>
                          <button>clear all</button>
                           <button>clear</button>  
                       </div>  
            
                       <div>
                           <button>all</button>
                           <button>active</button>
                           <button>completed</button>
                       </div>
                  </div>
           </div>

       

  </div>
</template>

<script>



export default {
  name:"App",

}
</script>


<style>
     
      #flex{
        
        display: flex;
        justify-content: center;
      }

     body{
       background-color: rgb(51, 51, 94);
       color: white;
       text-align: center;
     }
     #app{
       width: 100%;
     }
     #text{
       background-color: rgb(20, 19, 31);
       border: none;
       outline: none;
       text-align: center;
       border-bottom: 1px solid salmon;
         width:400px;
         padding: 5px;
         height: 30px;
         color: white;
         border-radius: 10px;
     }
     
     .x:hover{
       cursor: pointer;
     } 
     .x{
       margin-left: auto;
       background-color: rgb(20, 19, 31);
       font-size: 1.5em;
       border: none;
       color: whitesmoke;
     }

     .check{
        width: 30px;
        height: 35px;
     }
      ::placeholder{
        color: rgb(228, 222, 222);
        text-align: center;
        font-size: 1.5em;
      }

      #todo-button button{
        background-color: rgb(20, 19, 31);
        border: none;
        color: tomato;
      }

      #todo-button button:hover{

          text-decoration: underline;
          cursor: pointer;
      }

     #todo-button{
       padding: 10px  10px 5px 10px;
       display: flex;
       justify-content: space-between;

     
     }
      .todo .check{
       margin-right: 10px;
      }
     .todo{
        display: flex;
        padding: 10px;
        border-bottom: 1px solid rgb(88, 85, 85);
     }
  
     #todo{

             margin-top: 20px;
       background-color: rgb(20, 19, 31);
       width: 600px;
       margin-left: auto;
       margin-right: auto;
     }


</style>
