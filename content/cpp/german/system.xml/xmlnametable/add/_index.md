---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, atomisiert sie die angegebene Zeichenkette und fügt sie zur XmlNameTable hinzu.
type: docs
weight: 14
url: /de/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) Methode


Wenn sie in einer abgeleiteten Klasse überschrieben wird, atomisiert sie die angegebene Zeichenkette und fügt sie zu dem [XmlNameTable](../) hinzu.

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Das Zeichenarray, das den hinzuzufügenden Namen enthält. |
| offset | **int32_t** | Nullbasierter Index in das Array, der das erste Zeichen des Namens angibt. |
| length | **int32_t** | Die Anzahl der Zeichen im Namen. |

### Rückgabewert

Die neu atomisierte Zeichenkette oder die bereits vorhandene, falls sie bereits existiert. Wenn die Länge null ist, wird [String::Empty](../../../system/string/empty/) zurückgegeben.

## XmlNameTable::Add(const String\&) Methode


Wenn sie in einer abgeleiteten Klasse überschrieben wird, atomisiert sie die angegebene Zeichenkette und fügt sie zu dem [XmlNameTable](../) hinzu.

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Der hinzuzufügende Name. |

### Rückgabewert

Die neu atomisierte Zeichenkette oder die bereits vorhandene, falls sie bereits existiert.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNameTable](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)