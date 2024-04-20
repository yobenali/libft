# Libft

Welcome to Libft! This project is part of the 42 Network curriculum, aimed at improving your C programming skills by creating your own library of useful functions.

## About

Libft is a collection of standard C functions, along with some additional utility functions, carefully crafted to cover a wide range of programming tasks. Below are some of the major functions included in this library:

### Memory Management

- `void *ft_memset(void *s, int c, size_t n)`: Fills memory with a constant byte.
- `void *ft_memcpy(void *dest, const void *src, size_t n)`: Copies memory area.
- `void *ft_memmove(void *dest, const void *src, size_t n)`: Copies memory area, even if the memory blocks overlap.

### String Manipulation

- `size_t ft_strlen(const char *s)`: Calculates the length of a string.
- `char *ft_strcpy(char *dest, const char *src)`: Copies a string.
- `char *ft_strncpy(char *dest, const char *src, size_t n)`: Copies a string, but with a specified maximum length.

### Linked List Management

- `t_list *ft_lstnew(void *content)`: Allocates and initializes a new list element.
- `void ft_lstadd_front(t_list **lst, t_list *new)`: Adds a new element at the beginning of a list.
- `void ft_lstiter(t_list *lst, void (*f)(void *))`: Iterates the list and applies a function to each element.

### Character Classification

- `int ft_isalpha(int c)`: Checks for an alphabetic character.
- `int ft_isdigit(int c)`: Checks for a digit.## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
- `int ft_isalnum(int c)`: Checks for an alphanumeric character.

## Usage

To use this library, clone the repository and compile it using the provided Makefile. Then, include the `libft.h` header file in your source files and link against the `libft.a` library.


## Contributions

Contributions and improvements are welcome! If you find any bugs or have suggestions for new functions, feel free to open an issue or submit a pull request.

