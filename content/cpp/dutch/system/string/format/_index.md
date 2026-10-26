---
title: Format()
second_title: Aspose.Slides voor C++ API Referentie
description: Formatteert een string in C#-stijl.
type: docs
weight: 885
url: /nl/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) methode

Formateert een string in C#-stijl.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Args | Argumenten om de string te formatteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formaatprovider die wordt gebruikt om argumenten naar strings te converteren. |
| format | const [String](../)\& | Opmaakstring. |
| args | const Args\&... | Argumenten om de string te formatteren. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) methode

Formateert een string in C#-stijl.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Args | Argumenten om de string te formatteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | std::nullptr_t | Opmaakstring. |
| args | const [String](../)\& | Argumenten om de string te formatteren. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) methode

Formateert een string in C#-stijl.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Args | Argumenten om de string te formatteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | std::nullptr_t | Opmaakstring. |
| args | const char16_t(&) | Argumenten om de string te formatteren. |

## String::Format(const String\&, const Args\&...) methode

Formateert een string in C#-stijl.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Args | Argumenten om de string te formatteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../)\& | Opmaakstring. |
| args | const Args\&... | Argumenten om de string te formatteren. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) methode

Formateert een string in C#-stijl.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Argumenten om de string te formatteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | const [String](../)\& | Opmaakstring. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Argumenten om de string te formatteren. |

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)