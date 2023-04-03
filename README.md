# _Printf

Making a printf function at holberton school

![5144313](https://user-images.githubusercontent.com/58869893/229312957-ffc049e8-153f-4c54-b1cb-6690606443c0.jpg)

## Desscription

the program receives a complex format that combines simple text with dynamic content housed in variables of different types to be printed on the screen.
It prints them in the indicated format and returns the number of characters printed.

## Installation

clone the repository, end use this flags to compilate the functions, add a main.c with cases to see it work with examples just like original printf.

```bash
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c
`````

## Usage

```Python


# returns the content of a string var
_printf("%s", stringVar)

# returns the content f a decimal var
_printf("%d", decimalv)

# returns the format indicated at first string with mixed content
_printf("Hola %i orientales, hoy es %s", numero, dia)

# whien var numero has a 33 value and var dia has the word Martes
Hola 33 orientales, hoy es Martes
`````
##Options
```
# d
print decimal vales
# i
print integer values
# c
print char values
# s
print a string
# '%'
print % character

`````
## Our flowchart

![Printf holberton](https://user-images.githubusercontent.com/58869893/229386768-ffd83ebe-745c-49fd-b73f-da0ee6442931.png)

## Authors

Pablo Riveiro y Lauro Villagra

