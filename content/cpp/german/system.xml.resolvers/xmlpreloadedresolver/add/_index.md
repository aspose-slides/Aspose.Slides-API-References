---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Byte-Array zum XmlPreloadedResolver-Speicher hinzu und ordnet es einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben.
type: docs
weight: 79
url: /de/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) Methode

Fügt ein Byte-Array zum [XmlPreloadedResolver](../)-Speicher hinzu und ordnet es einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Die URI der Daten, die zum [XmlPreloadedResolver](../)-Speicher hinzugefügt werden. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ein Byte-Array mit den Daten, die zur angegebenen URI gehören. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Fügt ein Byte-Array zum [XmlPreloadedResolver](../)-Speicher hinzu und ordnet es einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Die URI der Daten, die zum [XmlPreloadedResolver](../)-Speicher hinzugefügt werden. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ein Byte-Array mit den Daten, die zur angegebenen URI gehören. |
| offset | **int32_t** | Der Versatz im bereitgestellten Byte-Array, an dem die Daten beginnen. |
| count | **int32_t** | Die Anzahl der Bytes, die aus dem Byte-Array ab dem angegebenen Versatz gelesen werden sollen. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) Methode

Fügt einen Stream zum [XmlPreloadedResolver](../)-Speicher hinzu und ordnet ihn einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Die URI der Daten, die zum [XmlPreloadedResolver](../)-Speicher hinzugefügt werden. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Ein Stream mit den Daten, die zur angegebenen URI gehören. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) Methode

Fügt eine Zeichenkette mit vorab geladenen Daten zum [XmlPreloadedResolver](../)-Speicher hinzu und ordnet sie einer URI zu. Wenn der Speicher bereits eine Zuordnung für dieselbe URI enthält, wird die vorhandene Zuordnung überschrieben.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | Die URI der Daten, die zum [XmlPreloadedResolver](../)-Speicher hinzugefügt werden. |
| value | const [String](../../../system/string/)\& | Ein [String](../../../system/string/) mit den Daten, die zur angegebenen URI gehören. |

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [XmlPreloadedResolver](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Xml::Resolvers](../../)
* Bibliothek [Aspose.Slides](../../../)