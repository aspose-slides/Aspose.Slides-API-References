---
title: AddEmbeddedFont()
second_title: Aspose.Slides C++ API-referencia
description: Hozzáadja a beágyazott betűtípust.
type: docs
weight: 105
url: /hu/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) metódus


Hozzáadja a beágyazott betűtípust.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Font data object [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |
## Megjegyzés


Ne feledje, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll, amikor betűtípusokat másol. Először keresse meg a betűtípus licencét, és ellenőrizze, hogy szabadon áthelyezhető-e egy másik gépre.


## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) metódus


Hozzáadja a beágyazott betűtípust

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Font data **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Embedded font rule [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |
## Megjegyzés


Ne feledje, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll, amikor betűtípusokat ad hozzá. Először keresse meg a betűtípus licencét, és ellenőrizze, hogy szabadon áthelyezhető-e egy másik gépre.


## Lásd még

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)