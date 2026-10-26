---
title: operator+()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Operátor pro spojování řetězců.
type: docs
weight: 274
url: /cs/system/string/operator_plus/
---
## String::operator+(const String\&) const metoda


[String](../) operátor konkatenace.

```cpp
String System::String::operator+(const String &str) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) pro přidání na konec aktuálního. |

### Návratová hodnota

Spojený řetězec.

## String::operator+(const T\&) const metoda


[String](../) konkatenace s řetězcovým literálem nebo ukazatelem na znakový řetězec.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Jedna z forem řetězcového literálu nebo ukazatele na znakový řetězec. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arg | const T\& | Entita pro konkatenaci s aktuálním řetězcem. |

### Návratová hodnota

Spojený řetězec.

## String::operator+(char_t) const metoda


```cpp
String System::String::operator+(char_t x) const
```

Přidá znak na konec řetězce.

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | char_t | Znak k přidání. |

### Návratová hodnota

[String](../) výsledek konkatenace.

## String::operator+(int) const metoda


```cpp
String System::String::operator+(int i) const
```

Přidá řetězcovou reprezentaci celočíselné hodnoty na konec řetězce.

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | int | Celočíselná hodnota k převodu na řetězec a přidání. |

### Návratová hodnota

[String](../) výsledek konkatenace.

## String::operator+(uint32_t) const metoda


```cpp
String System::String::operator+(uint32_t i) const
```

Přidá řetězcovou reprezentaci nezáporné celočíselné hodnoty na konec řetězce.

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | **uint32_t** | Hodnota k převodu na řetězec a přidání. |

### Návratová hodnota

[String](../) výsledek konkatenace.

## String::operator+(double) const metoda


```cpp
String System::String::operator+(double d) const
```

Přidá řetězcovou reprezentaci čísla s plovoucí řádovou čárkou na konec řetězce.

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| d | **double** | Hodnota k převodu na řetězec a přidání. |

### Návratová hodnota

[String](../) výsledek konkatenace.

## String::operator+(int64_t) const metoda


```cpp
String System::String::operator+(int64_t v) const
```

Přidá řetězcovou reprezentaci celočíselné hodnoty na konec řetězce.

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| v | **int64_t** | Hodnota k převodu na řetězec a přidání. |

### Návratová hodnota

[String](../) výsledek konkatenace.

## String::operator+(const T\&) const metoda


```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

Přidá řetězcovou reprezentaci objektu referenčního typu na konec řetězce.

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | ukazatelový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) pro převod na řetězec pomocí volání [ToString()](../tostring/) a přidání k aktuálnímu řetězci. |

### Návratová hodnota

[String](../) výsledek konkatenace.

## String::operator+(const T\&) const metoda


```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

Přidá řetězcovou reprezentaci objektu hodnotového typu na konec řetězce.

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Hodnotový typ, na kterém se volá [ToString()](../tostring/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) pro převod na řetězec pomocí volání [ToString()](../tostring/) a přidání k aktuálnímu řetězci. |

### Návratová hodnota

[String](../) výsledek konkatenace.

## String::operator+(T) const metoda


```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

Přidá řetězcovou reprezentaci boolean hodnoty na konec řetězce.

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Hodnotový typ pro konkatenaci s řetězcem. Musí být bool |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) hodnota k převodu na řetězec a přidání. |

### Návratová hodnota

[String](../) výsledek konkatenace.

## Viz také

* Třída [String](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)