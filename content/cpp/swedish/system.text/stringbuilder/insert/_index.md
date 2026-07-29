---
title: Insert()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en sträng i byggarens fasta position.
type: docs
weight: 183
url: /sv/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) metod

Infogar en sträng i byggarens fasta position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Position där tecken ska infogas. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) att infoga. |

### Returvärde

Denna pekare.

## StringBuilder::Insert(int32_t, const String\&, int32_t) metod

Infogar en upprepad sträng i byggarens fasta position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Position där tecken ska infogas. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) att infoga. |
| count | **int32_t** | Hur många gånger **value**-strängen ska upprepas. |

### Returvärde

Denna pekare.

## StringBuilder::Insert(int, char_t) metod

Infogar tecken i byggarens fasta position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Position där tecken ska infogas. |
| ch | char_t | Tecken att infoga. |

### Returvärde

Denna pekare.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) metod

Infogar tecken i byggarens fasta position.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position där tecken ska infogas. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) att infoga del från. |
| startIndex | int | [Array](../../../system/array/) delens startindex. |
| charCount | int | [Array](../../../system/array/) delens längd. |

### Returvärde

Denna pekare.

## StringBuilder::Insert(int, T) metod

Infogar värde i byggarens fasta position.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Parameter | typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Position där tecken ska infogas. |
| value | T | Värde att formatera och infoga. |

### Returvärde

Denna pekare.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [StringBuilder](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)