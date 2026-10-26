---
title: WriteRaw()
second_title: Riferimento API Aspose.Slides per C++
description: Scrive markup grezzo manualmente da un buffer di caratteri.
type: docs
weight: 417
url: /it/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) metodo

Scrive markup grezzo manualmente da un buffer di caratteri.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Array di caratteri contenente il testo da scrivere. |
| index | **int32_t** | La posizione nel buffer che indica l'inizio del testo da scrivere. |
| count | **int32_t** | Il numero di caratteri da scrivere. |

## XmlTextWriter::WriteRaw(const String\&) metodo

Scrive markup grezzo manualmente da una stringa.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) contenente il testo da scrivere. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)