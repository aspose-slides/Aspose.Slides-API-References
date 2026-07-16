---
title: WriteFont()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit les données en base64 dans le document HTML lui-même
type: docs
weight: 105
url: /fr/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) méthode

Écrit les données en base64 dans le document HTML lui-même

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Générateur HTML |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Police à sérialiser |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Police substituée (si la substitution de police s'est produite), null sinon |
| fontStyle | [System::String](../../../system/string/) | Style de police |
| fontWeight | [System::String](../../../system/string/) | Poids de police |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Données de police |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IFontData](../../../aspose.slides/ifontdata/)
* Classe [String](../../../system/string/)
* Classe [EmbedAllFontsHtmlController](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)