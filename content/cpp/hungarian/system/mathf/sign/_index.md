---
title: Sign()
second_title: Aspose.Slides C++ API hivatkozás
description: Meghatározza a megadott előjeles integrális érték előjelét.
type: docs
weight: 274
url: /hu/system/mathf/sign/
---
## MathF::Sign(T) metódus


Meghatározza a megadott előjeles integrális érték előjelét.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az előjeles integrális típus |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T | Az érték, amelynek az előjelét meghatározzuk |

### Visszatérési érték

- 1 ha **value** kisebb, mint 0; 0 ha **value** egyenlő 0-val; 1 ha **value** nagyobb, mint 0

## MathF::Sign(T) metódus


Meghatározza a megadott lebegőpontos érték előjelét.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az argumentum lebegőpontos típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T | Az érték, amelynek az előjelét meghatározzuk |

### Visszatérési érték

- 1 ha **value** kisebb, mint 0; 0 ha **value** egyenlő 0-val; 1 ha **value** nagyobb, mint 0

## Lásd még

* Struktúra [MathF](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)