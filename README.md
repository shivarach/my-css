### CSS cheatsheet
* To disable outline foucs of an input box
    * `input:focus {
           outline: none;
         }`
 * To disable outline and background on button click or hover
    * `button:focus, button:hover {
                    background-color: $color-grey-darkest !important;
                    box-shadow: none;
                  }`
  * To adjust width of a button or any element based on cotent
    * `width: max-content`
    
#### Flexbox
* Apply flex and direction to the parent container
    * ```
      .container-1 {
             display: flex;
             /*
             align-items: flex-start;
             align-items: flex-end;
             align-items: center;
             flex-direction: column;
              */
         }

         .box-1 {
             flex: 2;
             order: 2;
         }
         
         .box-2 {
             flex: 1;
             order: 1;
         }
         ```
* Flex can be applied nestedly