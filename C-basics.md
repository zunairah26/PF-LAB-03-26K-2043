# data types
 |Data Type|Description| 
 |---|---|
 |int |Integers are whole numbers that can have both zero, positive and negative values but no decimal values It can take 232 distinct states from 2147483648 to 2147483647|
 |float |Floating type variables can hold real numbers precision of 6 digits|
 | double| Stores double-precision fractional numbers for higher accuracy. |
 | char | Stores a single character, letter, or ASCII value. |
 | bool | Stores a boolean value representing either `true` or `false`. |
 | void | Represents the absence of a value or type. |
 # Format specifiers:
 | Format Specifier | Description |
| :--- | :--- |
| `%d` | Signed decimal integer |
| `%u` | Unsigned decimal integer |
| `%o` | Unsigned octal number |
| `%x` | Unsigned hexadecimal number (lowercase) |
| `%X` | Unsigned hexadecimal number (uppercase) |
| `%f` | Decimal floating-point number |
| `%e` | Scientific notation (lowercase 'e') |
| `%c` | Single character |
| `%s` | String of characters |
| `%ld` | Signed long decimal integer |
# Input/Output Functions
| Function | Description |
| :--- | :--- |
| `scanf()` | Reads formatted data from standard input using format specifiers. |
| `printf()` | Outputs formatted text and variable values to standard output. |
| `getchar()` | Reads a single character from standard input. |
| `putchar()` | Displays a single character passed to it onto standard output. |
| `fgets()` | Reads a full line of text safely up to a specified size limit. |
| `puts()` | Writes a complete string to standard output and automatically appends a newline. |
# Escape Sequences
| Escape Sequence | Name | Example Usage & Description |
| :--- | :--- | :--- |
| `\n` | Newline | `printf("Hello\nWorld");` — Moves cursor to the next line. |
| `\t` | Horizontal Tab | `printf("Name:\tJohn");` — Inserts a tab space. |
| `\\` | Backslash | `printf("Path: C:\\data");` — Prints a literal backslash. |
| `\"` | Double Quote | `printf("He said, \"Hi\"");` — Prints double quotes. |
| `\a` | Alert / Bell | `printf("\a");` — Triggers a system beep. |
# Precision in Floating-Point Output
| Precision Concept | Description | Code Example | Output |
| :--- | :--- | :--- | :--- |
| **Specification** | Place a dot (`.`) followed by an integer specifying the decimal places between `%` and `f`. | `printf("%.2f", 3.14159);` | `3.14` |
| **Rounding** | Automatically rounds the last visible digit up or down. | `printf("%.1f", 5.678);` | `5.7` |


  
