---
title: WriteRaw()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, schrijft ruwe markup handmatig vanuit een tekenbuffer.
type: docs
weight: 287
url: /nl/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) methode

Wanneer overschreven in een afgeleide klasse, schrijft ruwe markup handmatig vanuit een tekenbuffer.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Tekenreeks die de te schrijven tekst bevat. |
| index | **int32_t** | De positie in de buffer die het begin van de te schrijven tekst aangeeft. |
| count | **int32_t** | Het aantal tekens dat moet worden geschreven. |

## XmlWriter::WriteRaw(const String\&) methode

Wanneer overschreven in een afgeleide klasse, schrijft ruwe markup handmatig vanuit een string.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) die de te schrijven tekst bevat. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlWriter](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)