---
title: MarkdownExportType
second_title: Aspose.Slides para la referencia de la API de C++
description: Tipo de documento de renderizado.
type: docs
weight: 950
url: /es/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum


Tipo de documento de renderizado.

```cpp
enum class MarkdownExportType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Sequential | 0 | Renderiza todos los elementos por separado. Uno a uno. |
| TextOnly | 1 | Renderiza solo texto. |
| Visual | 2 | Renderiza todos los elementos, los elementos que están agrupados - se renderizan juntos. |

## Observaciones


Ejemplo: 
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

## Ver también

* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)