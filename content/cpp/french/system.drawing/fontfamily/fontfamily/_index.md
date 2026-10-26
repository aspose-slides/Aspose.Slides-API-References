---
title: FontFamily()
second_title: Référence API Aspose.Slides pour C++
description: Construit une nouvelle instance de la classe FontFamily qui représente une famille de polices avec le nom spécifié.
type: docs
weight: 1
url: /fr/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) constructeur


Construit une nouvelle instance de la classe [FontFamily](../) qui représente une famille de polices avec le nom spécifié.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom d’une famille de polices |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) constructeur


Construit une nouvelle instance de [FontFamily](../) dans la FontCollection spécifiée avec le nom spécifié.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom d’une famille de polices |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | La FontCollection qui contient cette instance. |

## FontFamily::FontFamily(Text::GenericFontFamilies) constructeur


Construit une nouvelle instance de [FontFamily](../) à partir de la famille de polices générique spécifiée.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | La valeur GenericFontFamilies pour construire le [FontFamily](../). |

## Voir aussi

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [FontFamily](../)
* Class [FontCollection](../../../system.drawing.text/fontcollection/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)