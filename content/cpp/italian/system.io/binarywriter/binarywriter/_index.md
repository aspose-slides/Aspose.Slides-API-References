---
title: BinaryWriter()
second_title: Aspose.Slides per C++ Riferimento API
description: Crea un'istanza della classe BinaryWriter che scrive dati sul flusso specificato utilizzando la codifica specificata.
type: docs
weight: 1
url: /it/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) costruttore

Crea un'istanza della classe [BinaryWriter](../) che scrive dati sul flusso specificato utilizzando la codifica specificata.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Il flusso di output |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da utilizzare |
| leaveopen | **bool** | Specifica se il flusso **stream** deve rimanere aperto (true) dopo che l'oggetto corrente è stato eliminato o meno (false) |

## Vedi anche

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [BinaryWriter](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)