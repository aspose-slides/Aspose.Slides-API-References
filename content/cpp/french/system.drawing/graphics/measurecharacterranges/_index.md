---
title: MeasureCharacterRanges()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un tableau de régions, chacune délimitant les positions de caractères dans la chaîne spécifiée.
type: docs
weight: 508
url: /fr/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) méthode

Renvoie un tableau de régions, chacune délimitant les positions de caractères dans la chaîne spécifiée.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | La chaîne à mesurer |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | La police utilisée lors de la mesure de la chaîne |
| layoutRect | [RectangleF](../../rectanglef/) | Le rectangle de mise en page utilisé lors de la mesure de la chaîne |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Le format de chaîne, contenant les plages de caractères à mesurer |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Region](../../region/)
* Classe [String](../../../system/string/)
* Classe [Font](../../font/)
* Classe [RectangleF](../../rectanglef/)
* Classe [StringFormat](../../stringformat/)
* Classe [Graphics](../)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)