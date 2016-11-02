Coercions

- `Number('532abc') -> NaN`
- `Number('532.78abc') -> NaN`
- `Number('532.78') -> 532.78`
- `parseInt('532abc') -> 532`
- `parseInt('532.78abc') -> 532`
- `parseFloat('532.78abc') -> 532.78`
- `String(123) -> '123'`
- `(123).toString() -> '123'`
- `String(true) -> 'true'`
- `false.toString() -> 'false'`

** Truthy and Falsey values **
- `Boolean(null) -> false`
- `Boolean(NaN) -> false`
- `Boolean(0) -> false`
- `Boolean('') -> false`
- `Boolean(undefined) -> false`
- `Boolean(anythingElse) -> true`
- `!!(anything) -> Boolean(anything)`

**Implicit Coercions**
- `+('123') -> 123`
- `123 + '123' -> '123123'`
- `123 + +('123') -> 246`
- `'123' * 3 -> 369`
- `'8' - '1' -> 7`
