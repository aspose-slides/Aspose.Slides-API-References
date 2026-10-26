---
title: Get()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, liefert sie die atomarisierte Zeichenkette, die dieselben Zeichen wie der angegebene Zeichenbereich im übergebenen Array enthält.
type: docs
weight: 1
url: /de/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) Methode


Wenn sie in einer abgeleiteten Klasse überschrieben wird, liefert sie die atomarisierte Zeichenkette, die dieselben Zeichen wie der angegebene Zeichenbereich im übergebenen Array enthält.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Das Zeichenarray, das den zu suchenden Namen enthält. |
| offset | **int32_t** | Der nullbasierte Index im Array, der das erste Zeichen des Namens angibt. |
| length | **int32_t** | Die Anzahl der Zeichen im Namen. |

### Rückgabewert

Die atomarisierte Zeichenkette oder **nullptr**, falls die Zeichenkette noch nicht atomarisiert wurde. Wenn **length** null ist, wird [String::Empty](../../../system/string/empty/) zurückgegeben.

## XmlNameTable::Get(const String\&) Methode


Wenn sie in einer abgeleiteten Klasse überschrieben wird, liefert sie die atomarisierte Zeichenkette, die denselben Wert wie die angegebene Zeichenkette enthält.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Der zu suchende Name. |

### Rückgabewert

Die atomarisierte Zeichenkette oder **nullptr**, falls die Zeichenkette noch nicht atomarisiert wurde.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)