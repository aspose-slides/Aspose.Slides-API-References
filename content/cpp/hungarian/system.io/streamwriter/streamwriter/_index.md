---
title: StreamWriter()
second_title: Aspose.Slides C++ API Referenciája
description: Létrehozza a StreamWriter objektum egy példányát, amely karaktereket ír a megadott alapfolyamra UTF-8 kódolás használatával és egy alapértelmezett 1024 bájtos méretű bufferrel.
type: docs
weight: 1
url: /hu/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) konstruktor


[StreamWriter](../) objektum egy példányát hozza létre, amely karaktereket ír a megadott alapfolyamra UTF-8 kódolás használatával és egy alapértelmezett 1024 bájtos méretű bufferrel.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | A karakterek írásához használandó alapfolyam |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) konstruktor


[StreamWriter](../) objektum egy példányát hozza létre, amely karaktereket ír a megadott alapfolyamra a megadott kódolás használatával és egy alapértelmezett 1024 bájtos méretű bufferrel.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | A karakterek írásához használandó alapfolyam |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) konstruktor


[StreamWriter](../) objektum egy példányát hozza létre, amely karaktereket ír a megadott alapfolyamra a megadott kódolás és a megadott méretű buffer használatával. Egy paraméter meghatározza, hogy a [StreamWriter](../) objektum megszűnésekor a alapfolyamot le kell-e zárni.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | A karakterek írásához használandó alapfolyam |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |
| buffer_size | int | A buffer minimális mérete bájtban |
| leave_open | **bool** | Meghatározza, hogy a jelenlegi [StreamWriter](../) objektum megszűnése után a alapfolyam nyitva maradjon-e |

## StreamWriter::StreamWriter(const String\&) konstruktor


[StreamWriter](../) objektum egy példányát hozza létre, amely karaktereket ír a megadott fájlba UTF-8 kódolás használatával és egy alapértelmezett 1024 bájtos méretű bufferrel.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A karakterek írásához használandó fájl elérési útja |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) konstruktor


[StreamWriter](../) objektum egy példányát hozza létre, amely karaktereket ír a megadott fájlba a megadott kódolás és egy alapértelmezett 1024 bájtos méretű buffer használatával. Egy paraméter meghatározza, hogy az adat a fájlhoz legyen-e fűzve vagy felül legyen-e írva.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A karakterek írásához használandó fájl elérési útja |
| append | **bool** | Meghatározza, hogy az adat a megadott fájlhoz legyen-e fűzve (true) vagy a fájl felül legyen-e írva (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) konstruktor


[StreamWriter](../) objektum egy példányát hozza létre, amely karaktereket ír a megadott fájlba a megadott kódolás és bufferméret használatával. Egy paraméter meghatározza, hogy az adat a fájlhoz legyen-e fűzve vagy felül legyen-e írva.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A karakterek írásához használandó fájl elérési útja |
| append | **bool** | Meghatározza, hogy az adat a megadott fájlhoz legyen-e fűzve (true) vagy a fájl felül legyen-e írva (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |
| buffer_size | int | A használandó buffer mérete |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Osztály [Stream](../../stream/)
* Osztály [StreamWriter](../)
* Osztály [String](../../../system/string/)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)