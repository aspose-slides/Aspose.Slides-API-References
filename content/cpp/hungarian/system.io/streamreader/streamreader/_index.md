---
title: StreamReader()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy StreamReader objektum példányt, amely a megadott alapul szolgáló streamből karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 1024 bájt méretű puffert.
type: docs
weight: 1
url: /hu/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott alapul szolgáló streamből karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 1024 bájt méretű puffert.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Az alapul szolgáló stream, amelyből a karaktereket olvas |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott alapul szolgáló streamből karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 1024 bájt méretű puffert. Egy paraméter határozza meg, hogy a bájtsorrendet jelző jelölő (BOM) felismerése legyen-e engedélyezve.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Az alapul szolgáló stream, amelyből a karaktereket olvas |
| detectEncodingFromByteOrderMarks | **bool** | Igaz, ha a bájtsorrendet jelző jelölőket a stream elején kell keresni, egyébként hamis |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott alapul szolgáló streamből karaktereket olvas a megadott kódolás használatával és egy alapértelmezett 1024 bájt méretű puffert.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Az alapul szolgáló stream, amelyből a karaktereket olvas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott alapul szolgáló streamből karaktereket olvas a megadott kódolás és egy alapértelmezett 1024 bájt méretű puffert. Egy paraméter határozza meg, hogy a bájtsorrendet jelző jelölő (BOM) felismerése legyen-e engedélyezve.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Az alapul szolgáló stream, amelyből a karaktereket olvas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |
| detectEncodingFromByteOrderMarks | **bool** | Igaz, ha a bájtsorrendet jelző jelölőket a stream elején kell keresni, egyébként hamis |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott alapul szolgáló streamből karaktereket olvas a megadott kódolás és a megadott méretű buffer használatával. Egy paraméter határozza meg, hogy a bájtsorrendet jelző jelölő (BOM) felismerése legyen-e engedélyezve.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Az alapul szolgáló stream, amelyből a karaktereket olvas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |
| detectEncodingFromByteOrderMarks | **bool** | Igaz, ha a bájtsorrendet jelző jelölőket a stream elején kell keresni, egyébként hamis |
| bufferSize | int | A buffer minimális mérete bájtban |

## StreamReader::StreamReader(const System::String\&) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott fájlból karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 4096 bájt méretű puffert.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | A fájl elérési útja, amelyből a karaktereket olvas |

## StreamReader::StreamReader(const System::String\&, bool) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott fájlból karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 4096 bájt méretű puffert. Egy paraméter határozza meg, hogy a bájtsorrendet jelző jelölő (BOM) felismerése legyen-e engedélyezve.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | A fájl elérési útja, amelyből a karaktereket olvas |
| detectEncodingFromByteOrderMarks | **bool** | Igaz, ha a bájtsorrendet jelző jelölőket a fájl elején kell keresni, egyébként hamis |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott fájlból karaktereket olvas a megadott kódolás használatával és egy alapértelmezett 4096 bájt méretű puffert.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | A fájl elérési útja, amelyből a karaktereket olvas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott alapul szolgáló streamből karaktereket olvas a megadott kódolás és egy alapértelmezett 4096 bájt méretű puffert. Egy paraméter határozza meg, hogy a bájtsorrendet jelző jelölő (BOM) felismerése legyen-e engedélyezve.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | A fájl elérési útja, amelyből a karaktereket olvas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |
| detectEncodingFromByteOrderMarks | **bool** | Igaz, ha a bájtsorrendet jelző jelölőket a fájl elején kell keresni, egyébként hamis |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) konstruktor


Létrehoz egy [StreamReader](../) objektumot, amely a megadott fájlból karaktereket olvas a megadott kódolás és a megadott méretű buffer használatával. Egy paraméter határozza meg, hogy a bájtsorrendet jelző jelölő (BOM) felismerése legyen-e engedélyezve.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | A fájl elérési útja, amelyből a karaktereket olvas |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |
| detectEncodingFromByteOrderMarks | **bool** | Igaz, ha a bájtsorrendet jelző jelölőket a fájl elején kell keresni, egyébként hamis |
| bufferSize | int | A buffer minimális mérete bájtban |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)