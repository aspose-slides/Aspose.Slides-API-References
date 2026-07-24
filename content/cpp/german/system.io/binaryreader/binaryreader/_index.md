---
title: BinaryReader()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine Instanz der BinaryReader-Klasse, die Daten aus dem angegebenen Stream mit UTF-8-Kodierung liest.
type: docs
weight: 1
url: /de/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) Konstruktor

Erstellt eine Instanz der [BinaryReader](../) Klasse, die Daten aus dem angegebenen Stream mit UTF-8-Kodierung liest.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der Eingabestream |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) Konstruktor

Erstellt eine Instanz der [BinaryReader](../) Klasse, die Daten aus dem angegebenen Stream mit der angegebenen Kodierung liest.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der Eingabestream |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Die zu verwendende Kodierung |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) Konstruktor

Erstellt eine Instanz der [BinaryReader](../) Klasse, die Daten aus dem angegebenen Stream mit der angegebenen Kodierung liest.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Der Eingabestream |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Die zu verwendende Kodierung |
| leaveOpen | **bool** | Gibt an, ob der Stream **input** nach der Entsorgung des aktuellen Objekts geöffnet bleiben soll (true) oder nicht (false) |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BinaryReader](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)