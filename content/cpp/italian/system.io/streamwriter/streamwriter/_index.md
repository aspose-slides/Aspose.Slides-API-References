---
title: StreamWriter()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'istanza dell'oggetto StreamWriter che scrive caratteri sullo stream sottostante specificato usando la codifica UTF-8 e un buffer con dimensione predefinita di 1024 byte.
type: docs
weight: 1
url: /it/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) costruttore

Costruisce un'istanza dell'oggetto [StreamWriter](../) che scrive caratteri sullo stream sottostante specificato usando la codifica UTF-8 e un buffer con dimensione predefinita di 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Lo stream sottostante su cui scrivere i caratteri |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) costruttore

Costruisce un'istanza dell'oggetto [StreamWriter](../) che scrive caratteri sullo stream sottostante specificato usando la codifica specificata e un buffer con dimensione predefinita di 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Lo stream sottostante su cui scrivere i caratteri |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da utilizzare |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) costruttore

Costruisce un'istanza dell'oggetto [StreamWriter](../) che scrive caratteri sullo stream sottostante specificato usando la codifica specificata e un buffer della dimensione specificata. Un parametro indica se lo stream sottostante deve essere chiuso quando l'oggetto [StreamWriter](../) viene eliminato.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Lo stream sottostante su cui scrivere i caratteri |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da utilizzare |
| buffer_size | int | La dimensione minima del buffer in byte |
| leave_open | **bool** | Specifica se lo stream sottostante deve rimanere aperto dopo che l'oggetto [StreamWriter](../) corrente è stato eliminato |

## StreamWriter::StreamWriter(const String\&) costruttore

Costruisce un'istanza dell'oggetto [StreamWriter](../) che scrive caratteri sul file specificato usando la codifica UTF-8 e un buffer con dimensione predefinita di 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file su cui scrivere i caratteri |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) costruttore

Costruisce un'istanza dell'oggetto [StreamWriter](../) che scrive caratteri sul file specificato usando la codifica specificata e un buffer con dimensione predefinita di 1024 byte. Un parametro indica se i dati devono essere aggiunti al file o se il file deve essere sovrascritto.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file su cui scrivere i caratteri |
| append | **bool** | Specifica se i dati devono essere aggiunti al file specificato (true) o se il file deve essere sovrascritto (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da utilizzare |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) costruttore

Costruisce un'istanza dell'oggetto [StreamWriter](../) che scrive caratteri sul file specificato usando la codifica specificata e la dimensione del buffer indicata. Un parametro indica se i dati devono essere aggiunti al file o se il file deve essere sovrascritto.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Il percorso del file su cui scrivere i caratteri |
| append | **bool** | Specifica se i dati devono essere aggiunti al file specificato (true) o se il file deve essere sovrascritto (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codifica da utilizzare |
| buffer_size | int | La dimensione del buffer da utilizzare |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)