---
title: FontFamily()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de FontFamily-klasse die een lettertypefamilie met de opgegeven naam vertegenwoordigt.
type: docs
weight: 1
url: /nl/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) constructor

Construeert een nieuw exemplaar van de klasse [FontFamily](../) die een lettertypefamilie met de opgegeven naam vertegenwoordigt.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Een lettertypefamilienaam |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) constructor

Construeert een nieuw exemplaar van [FontFamily](../) in de opgegeven FontCollection met de opgegeven naam.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Een lettertypefamilienaam |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | De FontCollection die deze instantie bevat. |

## FontFamily::FontFamily(Text::GenericFontFamilies) constructor

Construeert een nieuw exemplaar van [FontFamily](../) uit de opgegeven generieke lettertypefamilie.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | De GenericFontFamilies-waarde om de [FontFamily](../) te construeren. |

## Zie ook

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontFamily](../)
* Klasse [FontCollection](../../../system.drawing.text/fontcollection/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)