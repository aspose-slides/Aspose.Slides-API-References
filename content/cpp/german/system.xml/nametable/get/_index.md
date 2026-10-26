---
title: Get()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die atomisierte Zeichenkette mit dem angegebenen Wert zurück.
type: docs
weight: 27
url: /de/system.xml/nametable/get/
---
## NameTable::Get(const String\&) Methode


Gibt die atomisierte string mit dem angegebenen Wert zurück.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Der zu findende Name. |

### Rückgabewert

Das atomisierte string-Objekt oder **nullptr**, falls die string noch nicht atomisiert wurde.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) Methode


Gibt die atomisierte string zurück, die dieselben Zeichen wie der angegebene Bereich von Zeichen im gegebenen Array enthält.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Der Zeichen-Array, das den zu findenden Namen enthält. |
| start | **int32_t** | Der nullbasierte Index im Array, der das erste Zeichen des Namens angibt. |
| len | **int32_t** | Die Anzahl der Zeichen im Namen. |

### Rückgabewert

Die atomisierte string oder **nullptr**, falls die string noch nicht atomisiert wurde. Wenn **len** null ist, wird [String::Empty](../../../system/string/empty/) zurückgegeben.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)