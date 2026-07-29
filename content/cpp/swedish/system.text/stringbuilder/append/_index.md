---
title: Append()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till tecken till byggaren.
type: docs
weight: 118
url: /sv/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) metod

Lägger till tecken till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Teckenvärde. |

### Returvärde

Denna pekare.

## StringBuilder::Append(char_t, int) metod

Lägger till tecken till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Teckenvärde. |
| count | int | Hur många gånger tecknet ska upprepas. |

### Returvärde

Denna pekare.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) metod

Lägger till en teckenarray till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tecken att lägga till. |

### Returvärde

Denna pekare.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) metod

Lägger till ett utdrag av teckenarray till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tecken att lägga till. |
| startIndex | int | Utdragets startindex. |
| charCount | int | Utdragets längd. |

### Returvärde

Denna pekare.

## StringBuilder::Append(const String\&) metod

Lägger till en sträng till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) att lägga till. |

### Returvärde

Denna pekare.

## StringBuilder::Append(const String\&, int, int) metod

Lägger till ett strängutdrag till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) att lägga till. |
| startIndex | int | Utdragets startindex. |
| charCount | int | Utdragets längd. |

### Returvärde

Denna pekare.

## StringBuilder::Append(const SharedPtr\<T\>\&) metod

Lägger till objektets strängrepresentation till byggaren.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) att serialisera och lägga till. |

### Returvärde

Denna pekare.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) metod

Lägger till byggarens innehåll till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Byggare att lägga till innehåll från. |

### Returvärde

Denna pekare.

## StringBuilder::Append(float) metod

Lägger till ett flyttal till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | **float** | Värde att serialisera och lägga till. |

### Returvärde

Denna pekare.

## StringBuilder::Append(double) metod

Lägger till ett flyttal till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| df | **double** | Värde att serialisera och lägga till. |

### Returvärde

Denna pekare.

## StringBuilder::Append(int) metod

Lägger till ett heltalsvärde till byggaren.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| i | int | Värde att serialisera och lägga till. |

### Returvärde

Denna pekare.

## StringBuilder::Append(T) metod

Lägger till ett aritmetiskt värde till byggaren.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Aritmetisk typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T | Värde att serialisera och lägga till. |

### Returvärde

Denna pekare.

## StringBuilder::Append(E) metod

Lägger till en enumvärdes strängrepresentation till byggaren.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| E | [Enum](../../../system/enum/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | E | Värde att serialisera och lägga till. |

### Returvärde

Denna pekare.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [StringBuilder](../)
* Klass [String](../../../system/string/)
* Namnutrymme [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)