---
title: set_CompressionLevel()
second_title: Aspose.Slides per C++ Riferimento API
description: "Specifica il livello di compressione utilizzato durante il salvataggio del documento di presentazione. Il valore predefinito è CompressionLevel::Level6."
type: docs
weight: 92
url: /it/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metodo

Specifica il livello di compressione utilizzato durante il salvataggio del documento di presentazione. Il valore predefinito è [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
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
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)