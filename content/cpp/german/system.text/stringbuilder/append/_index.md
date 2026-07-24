---
title: Append()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Zeichen zum Builder hinzu.
type: docs
weight: 118
url: /de/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) Methode

Fügt ein Zeichen zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | char_t | Zeichenwert. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(char_t, int) Methode

Fügt Zeichen zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | char_t | Zeichenwert. |
| count | int | Wie oft das einzufügende Zeichen wiederholt werden soll. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) Methode

Fügt ein Zeichenarray zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Zeichen zum Hinzufügen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) Methode

Fügt einen Teil eines Zeichenarrays zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Zeichen zum Hinzufügen. |
| startIndex | int | Startindex des Ausschnitts. |
| charCount | int | Länge des Abschnitts. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(const String\&) Methode

Fügt eine Zeichenkette zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) zum Hinzufügen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(const String\&, int, int) Methode

Fügt einen Teil einer Zeichenkette zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) zum Hinzufügen. |
| startIndex | int | Startindex des Ausschnitts. |
| charCount | int | Länge des Abschnitts. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(const SharedPtr\<T\>\&) Methode

Fügt die Zeichenkettenrepräsentation des Objekts zum Builder hinzu.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../../system/object/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) zum Serialisieren und Hinzufügen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) Methode

Fügt den Inhalt des Builders zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder, von dem Inhalt hinzugefügt werden soll. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(float) Methode

Fügt einen Gleitkommawert zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| f | **float** | Wert zum Serialisieren und Hinzufügen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(double) Methode

Fügt einen Gleitkommawert zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| df | **double** | Wert zum Serialisieren und Hinzufügen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(int) Methode

Fügt einen Ganzzahlwert zum Builder hinzu.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| i | int | Wert zum Serialisieren und Hinzufügen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(T) Methode

Fügt einen arithmetischen Wert zum Builder hinzu.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Arithmetischer Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T | Wert zum Serialisieren und Hinzufügen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Append(E) Methode

Fügt die Zeichenkettenrepräsentation eines Enums zum Builder hinzu.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| E | [Enum](../../../system/enum/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| e | E | Wert zum Serialisieren und Hinzufügen. |

### Rückgabewert

Dieser Zeiger.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [StringBuilder](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)