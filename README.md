# pantone-to-hax6

List of pantone colors for dropdown 

![image](https://github.com/moinshaikh4607/pantone-to-hax6/assets/86479182/402eee84-3c28-4110-b285-6b2bb0329540)

dependecy :
- JQuery  >=3

options :

- prefix (default : '#')
- default (default : none)

return HEX6 by default

implementation :

  
    <select class="pantone" id="pantone">
         <option value="" selected>Select Color</option>  
    </select>
      
    <script>
            $(document).ready(function(){
                $(".pantone").pantone({
                    prefix:'',
                    default:'201547'
                });
            });
    </script> 
