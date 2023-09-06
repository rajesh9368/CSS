# CSS
In this project we are able to encounter various css properties while creating a website

          1. Filter 
          2. clip-path
          3. scale
          4.Box-shadow
          5.backround-clip,-webkit-background-clip,color:transparent(for image inside the text)
          6.bacground:linear-gradient(red,blue)(applying various patterns using to right ,to bottom sepaated by commas betwween aligning and color)
          7.Instagram-stories type background => set all div paddin, margin,width,height,content etc, and then apply linear-gradient property
          8.Css snippets to improve the reuseability of code and thus save our time rather writing code again and again.(settings -> user snippets -> css snippets )
          {
          "css snippet": {
		"prefix": "css",
		"body": [
			"* {",
			"    margin: 0;",
			"    padding: 0;",                                /*-----own created snippet in css ------------------*/
			"    box-sizing: border-box;",
				"}",
	
			"    html , body {",
			"    height: 100%;",
			"    width :100%;",
				"}"
		],
		"description": "boilerplate for css"	
	},
}

	9. Specific shadow is useed  to  apply to object only rather to whole div        filter:drop-shadow(vertical,horizontal,opacity,color);
        10. webkit_text-stroke:4px which is width of text and put color:transparent;
	11. Font-finder extension add this extension to your browser (left click mouse button --> font finder --> inspect) and then trace each word accordingly.
        12.Add color-extension zilla to your current browser and then search accordingly.(  color-azile --> in address bar from right hand side 4 option --> select it a clip path type icon appears) and search accordingly. 
	13.::selection(psedudo class)
        14. Javascript --> differ b/w a and b where a = numbervalue and b = stringvalue  difference in operation between (a+b=concatenation and a+ +b=sum)
	15.Javascript -->differ of operation between == and === operator.
        16. Scrollbar properties : body::-webkit-scrollbar{ color:transparent;}    body:-webkit-scrollbar-thumb{background:linear-gradient(red,blue,white,yellow); }
	17.Loader  making using html,css properties required border-radius:50%; border:5px solid grey; transition: rotate; @keyframes rotate{ 100%{rotate:360 deg;}}
 	18. Underline text (in nav bar transition) setting heading position to relative and heading::after{position:absolute;  left:0; bottom:0;transition:all ease 1s; height:3px;width; on hover h1:hover::after{width:100%;}
	
