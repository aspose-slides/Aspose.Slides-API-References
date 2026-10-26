---
title: set_CompressionLevel()
second_title: Riferimento API Aspose.Slides per C++
description: "Specifica il livello di compressione utilizzato durante il salvataggio del documento della presentazione. Il valore predefinito è CompressionLevel::Level6."
type: docs
weight: 92
url: /it/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metodo

Specifica il livello di compressione utilizzato durante il salvataggio del documento della presentazione. Il valore predefinito è [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Osservazioni

Livelli di compressione più elevati producono file più piccoli ma richiedono più tempo di elaborazione. Il rapporto di compressione effettivo dipende dal contenuto della presentazione. 

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Vedi anche

* Enum [CompressionLevel](../../compressionlevel/)
* Classe [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)