---
title: operator+()
second_title: Aspose.Slides für C++ API-Referenz
description: String-Verkettungsoperator.
type: docs
weight: 274
url: /de/system/string/operator_plus/
---
## String::operator+(const String\&) const Methode

[String](../) Verkettungsoperator.

```cpp
String System::String::operator+(const String &str) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) zum Anfügen an das Ende des aktuellen. |

### Rückgabewert

Verkettete Zeichenkette.

## String::operator+(const T\&) const Methode

[String](../) Verkettung mit Zeichenkettenliteral oder Zeichenkettenzeiger.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Eine der Formen von Zeichenkettenliteral oder Zeichenkettenzeiger. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg | const T\& | Entität, die mit der aktuellen Zeichenkette verkettet werden soll. |

### Rückgabewert

Verkettete Zeichenkette.

## String::operator+(char_t) const Methode

Fügt ein Zeichen am Ende der Zeichenkette hinzu.

```cpp
String System::String::operator+(char_t x) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | char_t | Zeichen zum Hinzufügen. |

### Rückgabewert

[String](../) Verkettungsergebnis.

## String::operator+(int) const Methode

Fügt die Zeichenketten-Darstellung eines ganzzahligen Werts am Ende der Zeichenkette hinzu.

```cpp
String System::String::operator+(int i) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | int | Ganzzahlwert, der in eine Zeichenkette konvertiert und hinzugefügt wird. |

### Rückgabewert

[String](../) Verkettungsergebnis.

## String::operator+(uint32_t) const Methode

Fügt die Zeichenketten-Darstellung eines vorzeichenlosen Ganzzahlwerts am Ende der Zeichenkette hinzu.

```cpp
String System::String::operator+(uint32_t i) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | **uint32_t** | Wert, der in eine Zeichenkette konvertiert und hinzugefügt wird. |

### Rückgabewert

[String](../) Verkettungsergebnis.

## String::operator+(double) const Methode

Fügt die Zeichenketten-Darstellung eines Gleitkommawerts am Ende der Zeichenkette hinzu.

```cpp
String System::String::operator+(double d) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | **double** | Wert, der in eine Zeichenkette konvertiert und hinzugefügt wird. |

### Rückgabewert

[String](../) Verkettungsergebnis.

## String::operator+(int64_t) const Methode

Fügt die Zeichenketten-Darstellung eines ganzzahligen Werts am Ende der Zeichenkette hinzu.

```cpp
String System::String::operator+(int64_t v) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| v | **int64_t** | Wert, der in eine Zeichenkette konvertiert und hinzugefügt werden soll. |

### Rückgabewert

[String](../) Verkettungsergebnis.

## String::operator+(const T\&) const Methode

Fügt die Zeichenketten-Darstellung eines Referenztyp-Objekts am Ende der Zeichenkette hinzu.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zeigertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) zur Konvertierung in eine Zeichenkette mittels [ToString()](../tostring/) Aufruf und zum Hinzufügen zur aktuellen Zeichenkette. |

### Rückgabewert

[String](../) Verkettungsergebnis.

## String::operator+(const T\&) const Methode

Fügt die Zeichenketten-Darstellung eines Werttyp-Objekts am Ende der Zeichenkette hinzu.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Werttyp, auf den [ToString()](../tostring/) aufgerufen wird. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) zur Konvertierung in eine Zeichenkette mittels [ToString()](../tostring/) Aufruf und zum Hinzufügen zur aktuellen Zeichenkette. |

### Rückgabewert

[String](../) Verkettungsergebnis.

## String::operator+(T) const Methode

Fügt die Zeichenketten-Darstellung eines booleschen Werts am Ende der Zeichenkette hinzu.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Werttyp, der mit der Zeichenkette verkettet wird. Muss bool sein |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) Wert zur Konvertierung in eine Zeichenkette und zum Hinzufügen. |

### Rückgabewert

[String](../) Verkettungsergebnis.

## Siehe auch

* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)