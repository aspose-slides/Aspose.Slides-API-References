---
title: StreamWriter()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří instanci objektu StreamWriter, který zapisuje znaky do určeného podkladového proudu pomocí kódování UTF-8 a vyrovnávací paměti s výchozí velikostí 1024 bajtů.
type: docs
weight: 1
url: /cs/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) konstruktor


Vytvoří instanci objektu [StreamWriter](../), který zapisuje znaky do určeného podkladového proudu pomocí kódování UTF-8 a vyrovnávací paměti s výchozí velikostí 1024 bajtů.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový proud, do kterého se mají zapisovat znaky |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) konstruktor


Vytvoří instanci objektu [StreamWriter](../), který zapisuje znaky do určeného podkladového proudu pomocí zadaného kódování a vyrovnávací paměti s výchozí velikostí 1024 bajtů.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový proud, do kterého se mají zapisovat znaky |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) konstruktor


Vytvoří instanci objektu [StreamWriter](../), který zapisuje znaky do určeného podkladového proudu pomocí zadaného kódování a vyrovnávací paměti o zadané velikosti. Parametr určuje, zda má být podkladový proud uzavřen, když je objekt [StreamWriter](../) uvolněn.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový proud, do kterého se mají zapisovat znaky |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |
| buffer_size | int | Minimální velikost vyrovnávací paměti v bajtech |
| leave_open | **bool** | Určuje, zda má být podkladový proud ponechán otevřený po uvolnění aktuálního objektu [StreamWriter](../) |

## StreamWriter::StreamWriter(const String\&) konstruktor


Vytvoří instanci objektu [StreamWriter](../), který zapisuje znaky do určeného souboru pomocí kódování UTF-8 a vyrovnávací paměti s výchozí velikostí 1024 bajtů.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, do kterého se mají zapisovat znaky |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) konstruktor


Vytvoří instanci objektu [StreamWriter](../), který zapisuje znaky do určeného souboru pomocí zadaného kódování a vyrovnávací paměti s výchozí velikostí 1024 bajtů. Parametr určuje, zda mají být data připojena k souboru nebo má být soubor přepsán.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, do kterého se mají zapisovat znaky |
| append | **bool** | Určuje, zda mají být data připojena k určenému souboru (true) nebo má být soubor přepsán (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) konstruktor


Vytvoří instanci objektu [StreamWriter](../), který zapisuje znaky do určeného souboru pomocí zadaného kódování a velikosti vyrovnávací paměti. Parametr určuje, zda mají být data připojena k souboru nebo má být soubor přepsán.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Cesta k souboru, do kterého se mají zapisovat znaky |
| append | **bool** | Určuje, zda mají být data připojena k určenému souboru (true) nebo má být soubor přepsán (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |
| buffer_size | int | Velikost vyrovnávací paměti, která se má použít |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)