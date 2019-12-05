# iostream for Python 3
The iostream library for Python 3.6+

# iostream functionalities:

## iostream(self, file="")
Sets the file for iostream to open.

## write(self, text)
Writes text to self.file using print. If "" then write using python stdout.

## read(self, text)
Reads using input. (Not supported for file read)


## Example using iostream
import iostream

stdio = iostream()

stdio.write("Hello World!")

will write Hello World to the output

or if line 2 was

stdio = iostream(file.txt)

the write will go to file.txt.
