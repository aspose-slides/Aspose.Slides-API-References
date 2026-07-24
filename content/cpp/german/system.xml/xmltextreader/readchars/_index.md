---
title: ReadChars()
second_title: Aspose.Slides für C++ API Referenz
description: Liest den Textinhalt eines Elements in einen Zeichenpuffer. Diese Methode ist dafür ausgelegt, große Datenströme eingebetteten Textes durch wiederholtes Aufrufen zu lesen.
type: docs
weight: 755
url: /de/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) Methode

Liest den Textinhalt eines Elements in einen Zeichenpuffer. Diese Methode ist dafür ausgelegt, große Datenströme eingebetteten Textes durch wiederholtes Aufrufen zu lesen.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Das Array von Zeichen, das als Puffer dient, in den die Textinhalte geschrieben werden. |
| index | **int32_t** | Die Position innerhalb von **buffer**, an der die Methode beginnen kann, Textinhalte zu schreiben. |
| count | **int32_t** | Die Anzahl der Zeichen, die in **buffer** geschrieben werden sollen. |

### Rückgabewert

Die Anzahl der gelesenen Zeichen. Dies kann 0 sein, wenn der Reader nicht auf einem Element positioniert ist oder wenn im aktuellen Kontext kein weiterer Textinhalt zurückzugeben ist.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlTextReader](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)