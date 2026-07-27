---
title: NewLineType
second_title: Referencia de API de Aspose.Slides para C++
description: Tipo de salto de línea que se utilizará en el documento generado.
type: docs
weight: 963
url: /es/aspose.slides.export/newlinetype/
---
## NewLineType enumeración

Tipo de salto de línea que se utilizará en el documento generado.

```cpp
enum class NewLineType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Windows | 0 | Nueva línea de DOS & Windows OS - \r\n |
| Unix | 1 | Nueva línea de Unix & Mac OS X - \n |
| Mac | 2 | Nueva línea de Mac (OS 9) - \r |

## Observaciones

Ejemplo
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"doc.md", System::IO::FileMode::OpenOrCreate);

System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(stream, slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Ver también

* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)