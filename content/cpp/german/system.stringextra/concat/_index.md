---
title: Concat()
second_title: Aspose.Slides für C++ API Referenz
description: Verkettet ein String-Array.
type: docs
weight: 1
url: /de/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) Funktion

Verkettet ein String-Array.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) von Strings zum Zusammenfügen. |

### Rückgabewert

Zusammengefügter String.

## System::StringExtra::Concat(const String\&, const String\&) Funktion

Verkettet Strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Erster String zum Zusammenfügen. |
| str1 | const [String](../../system/string/)\& | Zweiter String zum Zusammenfügen. |

### Rückgabewert

Zusammengefügte Parameter-Strings.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) Funktion

Verkettet Strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Erster String zum Zusammenfügen. |
| str1 | const [String](../../system/string/)\& | Zweiter String zum Zusammenfügen. |
| str2 | const [String](../../system/string/)\& | Dritter String zum Zusammenfügen. |

### Rückgabewert

Zusammengefügte Parameter-Strings.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) Funktion

Verkettet Strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Erster String zum Zusammenfügen. |
| str1 | const [String](../../system/string/)\& | Zweiter String zum Zusammenfügen. |
| str2 | const [String](../../system/string/)\& | Dritter String zum Zusammenfügen. |
| str3 | const [String](../../system/string/)\& | Vierter String zum Zusammenfügen. |

### Rückgabewert

Zusammengefügte Parameter-Strings.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) Funktion

Konvertiert mehrere Objekte zu String und verkettet die resultierenden Strings. Spezialisierung für [SmartPtr](../../system/smartptr/)-Typen.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) zum Konvertieren und Zusammenfügen. |

### Rückgabewert

[String](../../system/string/) Wert zusammengefügt aus den String-Darstellungen aller übergebenen Objekte.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) Funktion

Konvertiert mehrere Objekte zu String und verkettet die resultierenden Strings. Spezialisierung für arithmetische Typen.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) zum Konvertieren und Zusammenfügen. |

### Rückgabewert

[String](../../system/string/) Wert zusammengefügt aus den String-Darstellungen aller übergebenen Objekte.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) Funktion

Konvertiert mehrere Objekte zu String und verkettet die resultierenden Strings. Spezialisierung für Strukturen und andere Werttypen.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) zum Konvertieren und Zusammenfügen. |

### Rückgabewert

[String](../../system/string/) Wert zusammengefügt aus den String-Darstellungen aller übergebenen Objekte.

## Siehe auch

* Typedef [ArrayPtr](../../system/arrayptr/)
* Klasse [String](../../system/string/)
* Struktur [IsSmartPtr](../../system/issmartptr/)
* Namensraum [System::StringExtra](../)
* Bibliothek [Aspose.Slides](../../)