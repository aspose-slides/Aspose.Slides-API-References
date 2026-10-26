---
title: Read()
second_title: Aspose.Slides for C++ Referencja API
description: "Odczytuje schemat XML z dostarczonego IO::TextReader."
type: docs
weight: 365
url: /pl/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) metoda

Odczytuje XML [Schema](../../) z dostarczonego [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | [IO::TextReader](../../../system.io/textreader/) zawierający XML [Schema](../../) do odczytu. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Obsługa zdarzenia walidacji, która otrzymuje informacje o błędach składni XML [Schema](../../). |

### Wartość zwracana

Obiekt [XmlSchema](../) reprezentujący XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) metoda

Odczytuje XML [Schema](../../) z dostarczonego strumienia.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Dostarczony strumień danych. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Obsługa zdarzenia walidacji, która otrzymuje informacje o błędach składni XML [Schema](../../). |

### Wartość zwracana

Obiekt [XmlSchema](../) reprezentujący XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) metoda

Odczytuje XML [Schema](../../) z dostarczonego [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) zawierający XML [Schema](../../) do odczytu. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Obsługa zdarzenia walidacji, która otrzymuje informacje o błędach składni XML [Schema](../../). |

### Wartość zwracana

Obiekt [XmlSchema](../) reprezentujący XML [Schema](../../).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ValidationEventHandler](../../validationeventhandler/)
* Klasa [XmlSchema](../)
* Klasa [TextReader](../../../system.io/textreader/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [XmlReader](../../../system.xml/xmlreader/)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)