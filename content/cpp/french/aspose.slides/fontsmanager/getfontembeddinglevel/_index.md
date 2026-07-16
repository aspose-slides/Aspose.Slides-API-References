---
title: GetFontEmbeddingLevel()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine le niveau d'intégration d'une police à partir du tableau d'octets fourni et du nom de la police.
type: docs
weight: 144
url: /fr/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) method


Détermine le niveau d’intégration d’une police à partir du tableau d’octets fourni et du nom de la police.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d’octets contenant les données de la police. |
| fontName | [System::String](../../../system/string/) | Le nom de la police. |

### Valeur de retour

Le niveau d’intégration de la police spécifiée.

## Remarques




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## Voir aussi

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontsManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)