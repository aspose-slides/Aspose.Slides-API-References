---
title: ReadValueChunk()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest große Textströme, die in einem XML-Dokument eingebettet sind.
type: docs
weight: 807
url: /de/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) Methode

Liest große Textströme, die in einem XML-Dokument eingebettet sind.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Das Zeichenarray, das als Puffer dient, in den die Textinhalte geschrieben werden. Dieser Wert darf nicht **nullptr** sein. |
| index | **int32_t** | Der Offset innerhalb des Puffers, an dem [XmlReader](../) mit dem Kopieren der Ergebnisse beginnen kann. |
| count | **int32_t** | Die maximale Anzahl von Zeichen, die in den Puffer kopiert werden sollen. Die tatsächlich kopierte Zeichenanzahl wird von dieser Methode zurückgegeben. |

### Rückgabewert

Die Anzahl der in den Puffer gelesenen Zeichen. Der Wert null wird zurückgegeben, wenn kein weiterer Textinhalt mehr vorhanden ist.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)