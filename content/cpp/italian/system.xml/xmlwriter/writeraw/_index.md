---
title: WriteRaw()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, scrive markup grezzo manualmente da un buffer di caratteri.
type: docs
weight: 287
url: /it/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metodo

When overridden in a derived class, writes raw markup manually from a character buffer.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Array di caratteri contenente il testo da scrivere. |
| index | **int32_t** | La posizione nel buffer che indica l'inizio del testo da scrivere. |
| count | **int32_t** | Il numero di caratteri da scrivere. |

## XmlWriter::WriteRaw(const String\&) metodo

When overridden in a derived class, writes raw markup manually from a string.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) contenente il testo da scrivere. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlWriter](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)