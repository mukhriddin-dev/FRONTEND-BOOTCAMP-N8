## lesson-1

1. Grid 

- Grid container 
   1. justify-items: elememntlarni vertikal va gorizantal holatini belgilaydi: flex-start , flex-end , center ....
   2. align-items: vertikal yo'nalishda .....
   3. justify-content: gorizantal yo'nalishda ....
   4. grid-template-columns: ustunlarning holati:
   5. grid-template-rows: qatorlar holati:
   6. repeat( n , 100px) , minmax( 200px , 500px)
   

   ```
   .grid-container{
    border: 3px solid yellowgreen;
    display: grid;
    grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));
    grid-template-rows: repeat(4 , 200px);
}
   ```

- Grid Item
- Grid vs Flex
- Visullay hidden


- block / inline 
- inline-block
- none
- Flex
- grid 