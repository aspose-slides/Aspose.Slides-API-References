---
title: Concat()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een stringarray samen.
type: docs
weight: 1
url: /nl/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) function


Voegt een stringarray samen.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) van strings om te voegen. |

### Retourwaarde

Samengevoegde string.

## System::StringExtra::Concat(const String\&, const String\&) function


Voegt strings samen.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Eerste string om samen te voegen. |
| str1 | const [String](../../system/string/)\& | Tweede string om samen te voegen. |

### Retourwaarde

Samengevoegde parameterstringen.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) function


Voegt strings samen.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Eerste string om samen te voegen. |
| str1 | const [String](../../system/string/)\& | Tweede string om samen te voegen. |
| str2 | const [String](../../system/string/)\& | Derde string om samen te voegen. |

### Retourwaarde

Samengevoegde parameterstringen.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) function


Voegt strings samen.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Eerste string om samen te voegen. |
| str1 | const [String](../../system/string/)\& | Tweede string om samen te voegen. |
| str2 | const [String](../../system/string/)\& | Derde string om samen te voegen. |
| str3 | const [String](../../system/string/)\& | Vierde string om samen te voegen. |

### Retourwaarde

Samengevoegde parameterstringen.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


Converteert meerdere objecten naar een string en voegt de resulterende strings samen. Specialisatie voor [SmartPtr](../../system/smartptr/)-typen.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) om te converteren en te voegen. |

### Retourwaarde

[String](../../system/string/) waarde samengevoegd uit de stringrepresentaties van alle doorgegeven objecten.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


Converteert meerdere objecten naar een string en voegt de resulterende strings samen. Specialisatie voor rekenkundige typen.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) om te converteren en te voegen. |

### Retourwaarde

[String](../../system/string/) waarde samengevoegd uit de stringrepresentaties van alle doorgegeven objecten.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


Converteert meerdere objecten naar een string en voegt de resulterende strings samen. Specialisatie voor structuren en andere waardetypen.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) om te converteren en te voegen. |

### Retourwaarde

[String](../../system/string/) waarde samengevoegd uit de stringrepresentaties van alle doorgegeven objecten.

## Zie ook

* Typedef [ArrayPtr](../../system/arrayptr/)
* Klasse [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Naamruimte [System::StringExtra](../)
* Bibliotheek [Aspose.Slides](../../)