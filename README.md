 ~~~
 This is a coding example working on IRIS 2020.1 and on Caché 2018.1.3 
 It will not be kept in sync with new versions      
 It is also NOT serviced by InterSystems Support !   
~~~ 

# SUDOKU
A demo in traditional style COS  

This was written based on a previous trial in .XLS  
It is far from being perfect. Rather a challenge for   
improvement in all directions (code, interface, ...)  
So anyone feel invited to make it better.  
   
USER>d ^SUDOKU  
 ;; Welcome to this SUDOKU demo !  
 ;; you may solve your SUDOKU easier or create your own  
 ;; under each box entry you find a list  
 ;; of allowed values for this box  
 ;; fill in numbers 1..9 as you need  
 ;; to clear a box enter any character or blank  
 ;; to stop enter . or ,  for the solver enter ?  
 ;; navigate between boxes by cursor keys <>^v  
 ;;  
go:
