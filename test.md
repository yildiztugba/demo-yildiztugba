# Development strategy

## `for: Header`

### `type: html` (Header)

- div with class called "navbar"
- div with class called "container flex"
	- Title with h1 and class called "Logo"
	- nav
		- ul
			- li
				- a link(Home) with href "index.html"
				- a link (Features) with href "features.html"
				- a link (Docs) with href "docs.html"

### `type: css`(Header)

- "navbar": background-color, color, height
- "navbar ul": display
- "navbar a": color, padding, margin
- "navbar a:hover": border-bottom
- "navbar .flex": justify-content

## `for: Showcase`

### `type: html` (Showcase)

 - section with class called "showcase"
	 - div with class called "container grid"
		 -  div with class called showcase-text
			 - Title with h1
			 - Information with p
			 - a link with class called "btn btn-outline"
		- div with class called "showcase-form card"
			-  Title with h1
			-  form
				- div with class called "form-control"
					-  input with text type (required)
				-  div with class called "form-control"
					-  input with text type (required)
				-  div with class called "form-control"
					-  input with email type (required)
				-  input with submit type, class called "btn btn-primary"

### `type: css` (Showcase)

- "showcase": height,background-color,color,position
- "showcase h1": font-size
- "showcase p": margin
- "showcase grid":overflow,grid-template-columns,gap
- "showcase-text": animation
- "showcase-form":position,top,height,width,padding,z-index,justify-self,animation
- "showcase-form form-control": margin
- "showcase-form input[type='text']" ,"showcase-form input[type='email']":
	- border,border-bottom,width,padding,font-size
- "showcase-form input:focus": outline
- "showcase::before", "showcase::after"
	- content,position,height,bottom,right,left,background,transform,-webkit-transform,-moz-transform,ms-transform

## `for: Footer`

### `type: html` (Footer)

- footer with class called "footer bg-dark py-5"
- div with class called "container grid grid-3"
- div 
	- Title with h1
	- Text with p
- nav
	- ul
		- li
			- a link(Home) with href "index.html"
			- a link (Features) with href "features.html"
			- a link (Docs) with href "docs.html"
- div with class called "social"
	- A link(Github) with class called "fab fa-github fa-2x"
	- A link(Facebook) with class called "fab fa-facebook fa-2x"
	- A link(Instagram) with class called "fab fa-instagram fa-2x"
	- A link (Twitter) with class called "fab fa-twitter fa-2x"

### `type: css` (Footer)

- "footer .social a": margin
- "p": margin
- "h1": font-weight, line-height, margin
