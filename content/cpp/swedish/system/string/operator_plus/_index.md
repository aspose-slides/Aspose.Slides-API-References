---
title: operator+()
second_title: Aspose.Slides för C++ API-referens
description: Strängkonkateneringsoperator.
type: docs
weight: 274
url: /sv/system/string/operator_plus/
---
## String::operator+(const String\&) const metod

[String](../) konkateneringsoperator.

```cpp
String System::String::operator+(const String &str) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) för att lägga till i slutet av den aktuella. |

### Returvärde

Konkatenerad sträng.

## String::operator+(const T\&) const metod

[String](../) konkatenering med strängliteral eller teckensträngspekare.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | En av formerna strängliteral eller teckensträngspekare. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg | const T\& | Entitet som ska konkateneras med den aktuella strängen. |

### Returvärde

Konkatenerad sträng.

## String::operator+(char_t) const metod

Lägger till tecken i slutet av strängen.

```cpp
String System::String::operator+(char_t x) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | char_t | Tecken att lägga till. |

### Returvärde

[String](../) konkateneringsresultat.

## String::operator+(int) const metod

Lägger till heltalsvärdets strängrepresentation i slutet av strängen.

```cpp
String System::String::operator+(int i) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int | Heltalsvärde som ska konverteras till sträng och läggas till. |

### Returvärde

[String](../) konkateneringsresultat.

## String::operator+(uint32_t) const metod

Lägger till osignerat heltalets strängrepresentation i slutet av strängen.

```cpp
String System::String::operator+(uint32_t i) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | **uint32_t** | Värde som ska konverteras till sträng och läggas till. |

### Returvärde

[String](../) konkateneringsresultat.

## String::operator+(double) const metod

Lägger till flyttalsvärdets strängrepresentation i slutet av strängen.

```cpp
String System::String::operator+(double d) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | **double** | Värde som ska konverteras till sträng och läggas till. |

### Returvärde

[String](../) konkateneringsresultat.

## String::operator+(int64_t) const metod

Lägger till heltalsvärdets strängrepresentation i slutet av strängen.

```cpp
String System::String::operator+(int64_t v) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | **int64_t** | Värde som ska konverteras till sträng och läggas till. |

### Returvärde

[String](../) konkateneringsresultat.

## String::operator+(const T\&) const metod

Lägger till referenstypens objekts strängrepresentation i slutet av strängen.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) för att konvertera till sträng med [ToString()](../tostring/)-anrop och lägga till i den aktuella strängen. |

### Returvärde

[String](../) konkateneringsresultat.

## String::operator+(const T\&) const metod

Lägger till värdetypens objekts strängrepresentation i slutet av strängen.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp att anropa [ToString()](../tostring/) på. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) för att konvertera till sträng med [ToString()](../tostring/)-anrop och lägga till i den aktuella strängen. |

### Returvärde

[String](../) konkateneringsresultat.

## String::operator+(T) const metod

Lägger till booleanvärdets strängrepresentation i slutet av strängen.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp att konkatenera med sträng. Måste vara bool |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) värde att konvertera till sträng och lägga till. |

### Returvärde

[String](../) konkateneringsresultat.

## Se även

* Klass [String](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)