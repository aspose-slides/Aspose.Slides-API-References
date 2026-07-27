---
title: get_CompressionLevel()
second_title: Referência da API Aspose.Slides for C++
description: "Especifica o nível de compressão usado ao salvar o documento de apresentação. O valor padrão é CompressionLevel::Level6."
type: docs
weight: 79
url: /pt/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() método


Especifica o nível de compressão usado ao salvar o documento de apresentação. O valor padrão é [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Observações


Níveis de compressão mais altos produzem arquivos menores, mas requerem mais tempo de processamento. A taxa real de compressão depende do conteúdo da apresentação. 

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ver também

* Enum [CompressionLevel](../../compressionlevel/)
* Classe [PptxOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)