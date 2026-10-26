---
title: Add()
second_title: Aspose.Slides für C++ API Referenz
description: Atomisiert die angegebene Zeichenkette und fügt sie der NameTable hinzu.
type: docs
weight: 14
url: /de/system.xml/nametable/add/
---
## NameTable::Add(const String\&) Methode

Atomisiert die angegebene Zeichenkette und fügt sie dem [NameTable](../) hinzu.

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | Die Zeichenkette, die hinzugefügt werden soll. |

### Rückgabewert

Die atomisierte Zeichenkette oder die vorhandene Zeichenkette, falls sie bereits im [NameTable](../) existiert.

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) Methode

Atomisiert die angegebene Zeichenkette und fügt sie dem [NameTable](../) hinzu.

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Das Zeichenarray, das die hinzuzufügende Zeichenkette enthält. |
| start | **int32_t** | Der nullbasierte Index im Array, der das erste Zeichen der Zeichenkette angibt. |
| len | **int32_t** | Die Anzahl der Zeichen in der Zeichenkette. |

### Rückgabewert

Die atomisierte Zeichenkette oder die vorhandene Zeichenkette, falls bereits im [NameTable](../) vorhanden ist. Wenn **len** Null ist, wird [String::Empty](../../../system/string/empty/) zurückgegeben.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [NameTable](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)