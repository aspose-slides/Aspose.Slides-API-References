---
title: Sign()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a megadott aláírt integrális érték előjelét.
type: docs
weight: 274
url: /hu/system/math/sign/
---
## Math::Sign(T) metódus


Meghatározza a megadott aláírt egész érték előjelét.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az aláírt integrális típus |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T | Az érték, amelynek az előjelét meg kell határozni |

### Visszatérési érték

- 1 ha **value** kisebb, mint 0; 0 ha **value** egyenlő 0-val; 1 ha **value** nagyobb, mint 0

## Math::Sign(T) metódus


Meghatározza a megadott lebegőpontos érték előjelét.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az argumentum lebegőpontos típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T | Az érték, amelynek az előjelét meg kell határozni |

### Visszatérési érték

- 1 ha **value** kisebb, mint 0; 0 ha **value** egyenlő 0-val; 1 ha **value** nagyobb, mint 0

## Math::Sign(const Decimal\&) metódus


Meghatározza a megadott decimális érték előjelét.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Az érték, amelynek az előjelét meg kell határozni |

### Visszatérési érték

- 1 ha **value** kisebb, mint 0; 0 ha **value** egyenlő 0-val; 1 ha **value** nagyobb, mint 0

## Lásd még

* Osztály [Decimal](../../decimal/)
* Struktúra [Math](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)