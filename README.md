# ft_printf
Recreation of libc's printf function

## Subject


### Usage
To compile, run `make`. This will compile **libftprintf.a**.
Include `ft_printf.h` in your c file to use ft_printf (located inside includes directory).
Usage of the program is same as the real printf function.
Example main:
```c
#include "ft_printf.h"

int				main(void)
{
	ft_printf("%s, w%s\n", "Hello", "orld!");
	return (0);
}
```
