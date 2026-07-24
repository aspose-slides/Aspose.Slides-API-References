---
title: Format()
second_title: Aspose.Slides für C++ API Referenz
description: Formatiert eine Zeichenkette im C#-Stil.
type: docs
weight: 885
url: /de/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) Methode

Formatiert eine Zeichenkette im C#-Stil.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Args | Argumente zum Formatieren der Zeichenkette. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider, der zum Konvertieren der Argumente in Zeichenketten verwendet wird. |
| format | const [String](../)\& | Formatzeichenkette. |
| args | const Args\&... | Argumente zum Formatieren der Zeichenkette. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) Methode

Formatiert eine Zeichenkette im C#-Stil.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Args | Argumente zum Formatieren der Zeichenkette. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | std::nullptr_t | Formatzeichenkette. |
| args | const [String](../)\& | Argumente zum Formatieren der Zeichenkette. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) Methode

Formatiert eine Zeichenkette im C#-Stil.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Args | Argumente zum Formatieren der Zeichenkette. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | std::nullptr_t | Formatzeichenkette. |
| args | const char16_t(&) | Argumente zum Formatieren der Zeichenkette. |

## String::Format(const String\&, const Args\&...) Methode

Formatiert eine Zeichenkette im C#-Stil.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Args | Argumente zum Formatieren der Zeichenkette. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../)\& | Formatzeichenkette. |
| args | const Args\&... | Argumente zum Formatieren der Zeichenkette. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) Methode

Formatiert eine Zeichenkette im C#-Stil.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Argumente zum Formatieren der Zeichenkette. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../)\& | Formatzeichenkette. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Argumente zum Formatieren der Zeichenkette. |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)