---
title: Insert()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een string in op een vaste positie van de builder.
type: docs
weight: 183
url: /nl/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) methode


Voegt een string in op een vaste positie van de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Positie om tekens in te voegen. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) om in te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Insert(int32_t, const String\&, int32_t) methode


Voegt een herhaalde string in op een vaste positie van de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Positie om tekens in te voegen. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) om in te voegen. |
| count | **int32_t** | Hoe vaak de **value**-string moet worden herhaald. |

### Retourwaarde

Deze pointer.

## StringBuilder::Insert(int, char_t) methode


Voegt een teken in op een vaste positie van de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Positie om tekens in te voegen. |
| ch | char_t | Teken om in te voegen. |

### Retourwaarde

Deze pointer.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) methode


Voegt tekens in op een vaste positie van de builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om tekens in te voegen. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) om een slice van in te voegen. |
| startIndex | int | [Array](../../../system/array/) begindex van de slice. |
| charCount | int | [Array](../../../system/array/) slice lengte. |

### Retourwaarde

Deze pointer.

## StringBuilder::Insert(int, T) methode


Voegt een waarde in op een vaste positie van de builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Parameter | type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Positie om tekens in te voegen. |
| value | T | Waarde om te formatteren en in te voegen. |

### Retourwaarde

Deze pointer.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StringBuilder](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)