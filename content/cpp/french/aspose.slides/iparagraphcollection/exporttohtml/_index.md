---
title: ExportToHtml()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit les paragraphes spécifiés en HTML et le renvoie sous forme d'objet String.
type: docs
weight: 105
url: /fr/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) method


Convertit les paragraphes spécifiés en HTML et le renvoie sous forme d'objet String.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Index du premier paragraphe **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) nombre **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Options de conversion [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Valeur de retour

HTML généré.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Classe [IParagraphCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)