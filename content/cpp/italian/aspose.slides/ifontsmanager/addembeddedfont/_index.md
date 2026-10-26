---
title: AddEmbeddedFont()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge il font incorporato.
type: docs
weight: 105
url: /it/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) metodo


Aggiunge il font incorporato.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Oggetto dati del font [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Regola di incorporamento del font [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |
## Osservazioni


Tieni presente che, quando copi qualsiasi font, la maggior parte dei font è protetta da copyright. Prima individua la licenza di un font e verifica che possa essere trasferita liberamente su un'altra macchina.


## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) metodo


Aggiunge il font incorporato

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dati del font **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | Regola di incorporamento del font [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |
## Osservazioni


Tieni presente che, quando aggiungi qualsiasi font, la maggior parte dei font è protetta da copyright. Prima individua la licenza di un font e verifica che possa essere trasferita liberamente su un'altra macchina.


## Vedi anche

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)