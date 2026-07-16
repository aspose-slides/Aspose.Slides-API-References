---
title: MarkdownExportType
second_title: Référence de l'API Aspose.Slides pour C++
description: Type de rendu du document.
type: docs
weight: 950
url: /fr/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType énum

Type de rendu du document.

```cpp
enum class MarkdownExportType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Sequential | 0 | Rendre tous les éléments séparément. Un par un. |
| TextOnly | 1 | Rendre uniquement le texte. |
| Visual | 2 | Rendre tous les éléments, les éléments groupés - les rendre ensemble. |

## Remarques


Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Voir aussi

* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)