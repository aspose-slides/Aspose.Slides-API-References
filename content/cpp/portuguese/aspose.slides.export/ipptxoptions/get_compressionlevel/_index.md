---
title: get_CompressionLevel()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica o nível de compressão usado ao salvar o documento de apresentação. O valor padrão é CompressionLevel::Level6."
type: docs
weight: 79
url: /pt/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() método

Especifica o nível de compressão usado ao salvar o documento de apresentação. O valor padrão é [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Observações

Níveis de compressão mais altos produzem arquivos menores, mas exigem mais tempo de processamento. A taxa de compressão real depende do conteúdo da apresentação.

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Veja Também

* Enum [CompressionLevel](../../compressionlevel/)
* Classe [IPptxOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)