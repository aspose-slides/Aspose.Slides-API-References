---
title: AddEmbeddedFont()
second_title: Référence de l'API Aspose.Slides for C++
description: Ajoute la police intégrée.
type: docs
weight: 105
url: /fr/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) method


Ajoute la police intégrée.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Font data object [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |


## Remarques


Gardez à l’esprit que la plupart des polices sont protégées par le droit d’auteur lorsque vous les copiez. Localisez d’abord la licence d’une police et vérifiez qu’elle peut être librement transférée vers une autre machine.


## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) method


Ajoute la police intégrée

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Données de police **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Règle de police intégrée [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |


## Remarques


Gardez à l’esprit que la plupart des polices sont protégées par le droit d’auteur lors de l’ajout de polices. Localisez d’abord la licence d’une police et vérifiez qu’elle peut être librement transférée vers une autre machine.


## Voir aussi

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IFontData](../../ifontdata/)
* Classe [IFontsManager](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)