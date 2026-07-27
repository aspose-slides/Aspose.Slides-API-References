---
title: set_CompressionLevel()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica o nível de compressão usado ao salvar o documento da apresentação. O valor padrão é CompressionLevel::Level6."
type: docs
weight: 92
url: /pt/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) método


Especifica o nível de compressão usado ao salvar o documento da apresentação. O valor padrão é [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Observações


Níveis de compressão mais altos produzem arquivos menores, mas requerem mais tempo de processamento. A taxa de compressão real depende do conteúdo da apresentação. 

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ver Também

* Enum [CompressionLevel](../../compressionlevel/)
* Classe [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)