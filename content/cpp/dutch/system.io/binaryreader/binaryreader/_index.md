---
title: BinaryReader()
second_title: Aspose.Slides voor C++ API Referentie
description: Construeert een instantie van de BinaryReader-klasse die gegevens uit de opgegeven stroom leest met UTF-8-codering.
type: docs
weight: 1
url: /nl/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor


Construeert een instantie van de klasse [BinaryReader](../) die gegevens uit de opgegeven stroom leest met UTF-8-codering.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De invoerstroom |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Construeert een instantie van de klasse [BinaryReader](../) die gegevens uit de opgegeven stroom leest met de opgegeven codering.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De invoerstroom |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | De te gebruiken codering |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor


Construeert een instantie van de klasse [BinaryReader](../) die gegevens uit de opgegeven stroom leest met de opgegeven codering.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | De invoerstroom |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | De te gebruiken codering |
| leaveOpen | **bool** | Geeft aan of de **input**-stroom open moet blijven (true) nadat het huidige object is vrijgegeven, of niet (false) |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../stream/)
* Klasse [BinaryReader](../)
* Klasse [Encoding](../../../system.text/encoding/)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)