---
title: StreamReader()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine Instanz des StreamReader-Objekts, das Zeichen aus dem angegebenen zugrunde liegenden Stream mit UTF-8-Kodierung und einem Puffer mit einer Standardgröße von 1024 Bytes liest.
type: docs
weight: 1
url: /de/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus dem angegebenen zugrunde liegenden Stream mit UTF-8-Kodierung und einem Puffer mit einer Standardgröße von 1024 Bytes liest.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der zugrunde liegende Stream, aus dem Zeichen gelesen werden |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus dem angegebenen zugrunde liegenden Stream mit UTF-8-Kodierung und einem Puffer mit einer Standardgröße von 1024 Bytes liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Marks aktiviert werden soll.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der zugrunde liegende Stream, aus dem Zeichen gelesen werden |
| detectEncodingFromByteOrderMarks | **bool** | True, um am Anfang des Streams nach Byte Order Marks zu suchen, andernfalls false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus dem angegebenen zugrunde liegenden Stream mit der angegebenen Kodierung und einem Puffer mit einer Standardgröße von 1024 Bytes liest.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der zugrunde liegende Stream, aus dem Zeichen gelesen werden |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus dem angegebenen zugrunde liegenden Stream mit der angegebenen Kodierung und einem Puffer mit einer Standardgröße von 1024 Bytes liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Marks aktiviert werden soll.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der zugrunde liegende Stream, aus dem Zeichen gelesen werden |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |
| detectEncodingFromByteOrderMarks | **bool** | True, um am Anfang des Streams nach Byte Order Marks zu suchen, andernfalls false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus dem angegebenen zugrunde liegenden Stream mit der angegebenen Kodierung und einem Puffer der angegebenen Größe liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Marks aktiviert werden soll.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der zugrunde liegende Stream, aus dem Zeichen gelesen werden |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |
| detectEncodingFromByteOrderMarks | **bool** | True, um am Anfang des Streams nach Byte Order Marks zu suchen, andernfalls false |
| bufferSize | int | Die minimale Größe des Puffers in Bytes |

## StreamReader::StreamReader(const System::String\&) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus der angegebenen Datei mit UTF-8-Kodierung und einem Puffer mit einer Standardgröße von 4096 Bytes liest.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Der Pfad der Datei, aus der Zeichen gelesen werden |

## StreamReader::StreamReader(const System::String\&, bool) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus der angegebenen Datei mit UTF-8-Kodierung und einem Puffer mit einer Standardgröße von 4096 Bytes liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Marks aktiviert werden soll.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Der Pfad der Datei, aus der Zeichen gelesen werden |
| detectEncodingFromByteOrderMarks | **bool** | True, um am Anfang der Datei nach Byte Order Marks zu suchen, andernfalls false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus der angegebenen Datei mit der angegebenen Kodierung und einem Puffer mit einer Standardgröße von 4096 Bytes liest.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Der Pfad der Datei, aus der Zeichen gelesen werden |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus dem angegebenen zugrunde liegenden Stream mit der angegebenen Kodierung und einem Puffer mit einer Standardgröße von 4096 Bytes liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Marks aktiviert werden soll.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Der Pfad der Datei, aus der Zeichen gelesen werden |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |
| detectEncodingFromByteOrderMarks | **bool** | True, um am Anfang der Datei nach Byte Order Marks zu suchen, andernfalls false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor

Konstruiert eine Instanz des Objekts [StreamReader](../), das Zeichen aus der angegebenen Datei mit der angegebenen Kodierung und einem Puffer der angegebenen Größe liest. Ein Parameter gibt an, ob die Erkennung von Byte Order Marks aktiviert werden soll.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Der Pfad der Datei, aus der Zeichen gelesen werden |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Kodierung |
| detectEncodingFromByteOrderMarks | **bool** | True, um am Anfang der Datei nach Byte Order Marks zu suchen, andernfalls false |
| bufferSize | int | Die minimale Größe des Puffers in Bytes |

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)