---
title: IsNull()
second_title: Aspose.Slides für C++ API Referenz
description: Prüft, ob ein bestimmter Wert null ist. Version für arithmetische und Aufzählungstypen.
type: docs
weight: 1
url: /de/system/testtools/isnull/
---
## TestTools::IsNull(T) Methode


Überprüft, ob ein bestimmter Wert null ist. [Version](../../version/) für arithmetische und Aufzählungstypen.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des zu prüfenden Wertes. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T | Zu prüfender Wert auf Null. |

### Rückgabewert

Gibt immer false zurück.

## TestTools::IsNull(const T\&) Methode


Überprüft, ob ein bestimmter Wert null ist. [Version](../../version/) für nicht-arithmetische und nicht-Enum-Wertetypen.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des zu prüfenden Wertes. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | Zu prüfender Wert auf Null. |

### Rückgabewert

Wahr, wenn das Objekt mit nullptr als wahr verglichen wird, ansonsten falsch.

## TestTools::IsNull(const SharedPtr\<T\>\&) Methode


Überprüft, ob ein bestimmter Wert null ist. [Version](../../version/) für nicht-arithmetische Werttypen.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des zu prüfenden Wertes. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Zu prüfender Wert auf Null. |

### Rückgabewert

Wahr, wenn das Objekt mit nullptr als wahr verglichen wird, ansonsten falsch.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) Methode


Überprüft, ob ein bestimmter Wert null ist. [Version](../../version/) für Schlüssel-Wert-Paare.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| K | Schlüsseltyp. |
| V | Werttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Paarobjekt. |

### Rückgabewert

Wahr, wenn das Paar als null betrachtet wird, sonst falsch.

## TestTools::IsNull(const System::String\&) Methode


Überprüft, ob die Zeichenkette null ist.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) zum Prüfen. |

### Rückgabewert

Wahr, wenn die Zeichenkette als null betrachtet wird, sonst falsch.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Klasse [String](../../string/)
* Struktur [TestTools](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)