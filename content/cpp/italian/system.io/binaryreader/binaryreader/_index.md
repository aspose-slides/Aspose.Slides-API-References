---
title: BinaryReader()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'istanza della classe BinaryReader che legge i dati dallo stream specificato usando la codifica UTF-8.
type: docs
weight: 1
url: /it/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) costruttore

Crea un'istanza della classe [BinaryReader](../) che legge i dati dallo stream specificato usando la codifica UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Il flusso di input |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) costruttore

Crea un'istanza della classe [BinaryReader](../) che legge i dati dallo stream specificato usando la codifica specificata.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Il flusso di input |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | La codifica da utilizzare |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) costruttore

Crea un'istanza della classe [BinaryReader](../) che legge i dati dallo stream specificato usando la codifica specificata.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Il flusso di input |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | La codifica da utilizzare |
| leaveOpen | **bool** | Specifica se lo stream **input** deve rimanere aperto (true) dopo che l'oggetto corrente è stato eliminato oppure no (false) |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BinaryReader](../)
* Classe [Encoding](../../../system.text/encoding/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)