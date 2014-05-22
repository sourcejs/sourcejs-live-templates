# SourceJS Live templates

Live templates for WebStorm / Idea. Accelerate and simplify the development of specs in the IDE.

## Includes

* source.xml - basic set of templates.
* source-auxiliary.xml - set of templates for Odnoklassniki code styles.

### source.xml
<table>
    	<tr>
			<td>source</td>
			<td>source starting template</td>
		</tr>
		<tr>
			<td>sec</td>
			<td>source section</td>
		</tr>
		<tr>
			<td>cdc</td>
			<td>code example</td>
		</tr>
		<tr>
			<td>sex</td>
			<td>default source example block</td>
		</tr>
		<tr>
			<td>sex2</td>
			<td>source example block with 215px width</td>
		</tr>
		<tr>
			<td>sex3</td>
			<td>source example block with 730px width</td>
		</tr>
		<tr>
			<td>sex4</td>
			<td>source example block with 980px width</td>
		</tr>
		<tr>
			<td>sex5</td>
			<td>source example block with 1200px width</td>
		</tr>
		<tr>
			<td>sexa</td>
			<td>source example block with auto width</td>
		</tr>
		<tr>
			<td>sexf</td>
			<td>source example block with 100% width</td>
		</tr>
		<tr>
			<td>sas</td>
			<td>link to other source spec</td>
		</tr>
		<tr>
			<td>sad</td>
			<td>link to design spec</td>
		</tr>
		<tr>
			<td>info, warn, note, data, doc</td>
			<td>highlighted info blocks with some data</td>
		</tr>
	</table>

### source-OK.xml
<table>
		<tr>
			<td>ch1</td>
			<td>CSS comment 1 level</td>
		</tr>
		<tr>
			<td>ch2</td>
			<td>CSS comment 2 level</td>
		</tr>
		<tr>
			<td>ch3</td>
			<td>CSS comment 3 level</td>
		</tr>
		<tr>
			<td>ch4</td>
			<td>CSS comment 4 level</td>
		</tr>
		<tr>
			<td>hc1</td>
			<td>HTML comment 1 level</td>
		</tr>
		<tr>
			<td>hc2</td>
			<td>HTML comment 2 level</td>
		</tr>
		<tr>
			<td>hc3</td>
			<td>HTML comment 3 level</td>
		</tr>
		<tr>
			<td>hc4</td>
			<td>HTML comment 4 level</td>
		</tr>
		<tr>
			<td>jc1</td>
			<td>JS comment 1 level</td>
		</tr>
		<tr>
			<td>jc2</td>
			<td>JS comment 2 level</td>
		</tr>
		<tr>
			<td>jc3</td>
			<td>JS comment 3 level</td>
		</tr>
		<tr>
			<td>jc4</td>
			<td>JS comment 4 level</td>
		</tr>
		<tr>
			<td>tpltr</td>
			<td>mustache starter kit</td>
		</tr>
		<tr>
			<td>rdk</td>
			<td>rdk starter kit</td>
		</tr>
		<tr>
			<td>au</td>
			<td>spec author</td>
		</tr>
		<tr>
			<td>todo</td>
			<td>CSS or HTML todo comment</td>
		</tr>
		<tr>
			<td>cc</td>
			<td>clean check comment</td>
		</tr>
		<tr>
			<td>ref</td>
			<td>todo refactor</td>
		</tr>
	</table>


## How to use

1. Just copy need files to templates directory and then restart IDE.

    Templates directory on Windows:
    
    	username//.WebIdeXX/config/templates/
    OS X:
    
    	~/Library/Preferences/IntelliJIdeaXX/templates

    <br>
    
2. Make for each file symlinks:

	    ln -s source.xml ~/Library/Preferences/IntelliJIdeaXX/templates

### (c) Odnoklassniki front-end team