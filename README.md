# CSS-1

### CSS-3:
	What is css?
	What is full meaning of css?

### CSS Write 3 way:
	1) Inline CSS : This is use HTML any start tag. its call attribute ( Ex: style="color:blue;" )
			<p style="color:blue;"> </p>

	2) Internal CSS : This is use HTML in Head Tag after title tag. ( Ex: <style> color:blue; </style>)
			<style type="text/css"/>
			    h1{
			       color: #f00;
			        background: yellow;
			        text-align: center;
			        }
			</style>

	3) External CSS : This isn't use HTML edit page. But Its link up HTML page use link tag after title tag.
	            	  Its use new page. its extention name (.css)
			<head>
				<title> </title>
				<link href="/style.css" rel="stylesheet" type="text/css"/>
			</head>
			 and create a style page (style.css)

### TAG::
	Style Tag <style> </style>

### CSS SYNTAX: 
		Selector Property  Value
		  h1 {     color :  red;   }

### Selector's:
	1) Element Selector / Type Selector :
 	    ( EX:  p{} )      p { color:red; }

	2) Id Selector :
   	    ( EX: #idname {} )      #para { color:red; }

	3) Class Selector :
     	    ( EX:  classname{} )       .para { color:red; }

	4) Universal Selector :
   	    ( EX:*{} )        * { color:red; }
	
	5) Descendent Selector :
   	    ( EX:menu ul li{} )       menu ul li { color:red; }

	6) Group selector :
 	    ( EX:a,p,b{}  )	  a,p,b { color:red; }

	7) Attribute Selector :
    	    ( EX: input[type=text]{} )     input[type=text] { color:red; }

### Property:: ( Property:value; )
		Color: teal/ #000000/ 122 555 125 ;
		Text-align: left / right / center / justify ; 
		margin: top right bottom left (margin:2px 2px 2px 2px; ) - 4 value
			3 value- top left+right bottom
			2 value- top+bottom left+right
		padding:  top right bottom left (margin:2px 2px 2px 2px; ) - 4 value
			3 value- top left+right bottom
			2 value- top+bottom left+right
		Font-family: arial, verdana; (any use font style)
			You used spacing font must used qutation (font-family:"Times New Roman";)
		Font-size: 20px;
		Font-weight: bold; ( normal, bold, bolder, lighter, 100, 200, 300, 900)
		Font-style:italic;
		Font-variant: small-caps; (small-caps, normal)
	|
 
 ***
  ## G SARWAR
  ### Web Instructor
