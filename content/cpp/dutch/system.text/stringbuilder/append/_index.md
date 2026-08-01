---
title: Append()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een teken toe aan de builder.
type: docs
weight: 118
url: /nl/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) methode

Voegt een teken toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | char_t | Karakterwaarde. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(char_t, int) methode

Voegt tekens toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | char_t | Karakterwaarde. |
| count | int | Hoe vaak het in te voegen teken moet worden herhaald. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) methode

Voegt een tekenarray toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tekens om toe te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) methode

Voegt een deel van een tekenarray toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tekens om toe te voegen. |
| startIndex | int | Beginindex van het deel. |
| charCount | int | Lengte van het deel. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(const String\&) methode

Voegt een string toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) om toe te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(const String\&, int, int) methode

Voegt een deel van een string toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) om toe te voegen. |
| startIndex | int | Beginindex van het deel. |
| charCount | int | Lengte van het deel. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(const SharedPtr\<T\>\&) methode

Voegt de stringrepresentatie van een object toe aan de builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) om te serialiseren en toe te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) methode

Voegt de inhoud van de builder toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder waarvan de inhoud wordt toegevoegd. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(float) methode

Voegt een zwevend-kommagetal toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| f | **float** | Waarde om te serialiseren en toe te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(double) methode

Voegt een zwevend-kommagetal toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| df | **double** | Waarde om te serialiseren en toe te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(int) methode

Voegt een geheel getal toe aan de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | int | Waarde om te serialiseren en toe te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(T) methode

Voegt een rekenkundige waarde toe aan de builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Rekenkundig type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | Waarde om te serialiseren en toe te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Append(E) methode

Voegt de stringrepresentatie van een enum-waarde toe aan de builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| E | [Enum](../../../system/enum/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| e | E | Waarde om te serialiseren en toe te voegen. |

### Retourwaarde

Deze pointer.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [StringBuilder](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Text](../../)
* Library [Aspose.Slides](../../../)