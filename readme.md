# css
cascading style sheet    
extension is `.css`

## css structure
~~~css
selector {
  property: value;
}
~~~

# color
### color name like red, green, blue
### hexadecimal   
hexa = 6 (a to f)    
decimal = 10  (0 to 9)     
hexadecimal = 16 (0 to f)   
highest value `f` is white    
lowest value is `0` is black   
white hexadecimal value = `#ffffff`  
black hexadecimal value = `#00000`  
when first 3 letter is as last 3 letter you can omit last 3 digit. like `#fff`

### rgb() 
rgb stands for red, green, blue   
rgb() its a function. which require 3 parameter. red, green, blue   
rgb a value is `0 to 255`   
so hightest value `255` is white   
so lowest value `0` is black  
white rgb value = `rgb(255, 255, 255)`   
black rgb value = `rgb(0, 0, 0)`   

### rgba()   
rgba stands for red, green, blue, alpha.
rga will be like state above rga. 4th parameter `a` stands for `alpha`. which define transparency. transparency maximum value is 1 and minimum value is 0.   
suppose I want black color with 50% transparency so value will be `rgba(0, 0, 0, 0,5)`    

# unit  
absolute unit: 
* px
* pt

relative unit:  
* em
* %
* rem

# font 
there are 3 types font   
* serif (with tail)
* sans-serif (without tail)
* monospace

# spacing - clockwise
* margin   
margin will make spacing outside of container   
margin property:   
`margin` `margin-top` `margin-right` `margin-bottom` `margin-left`
  
* padding
padding will make spacing inside of container   
padding property:    
 `padding` `padding-top` `padding-right` `padding-bottom` `padding-left`   

### selector  - 5 selector
tag selector is tag name     
id selector start with `#`     
class selector start with `.`     
attribute selector encapsulate inside `[]`     
pseudo selector start with `:`. Generally we will place `pseduo` selector after earlier 4 selector 











