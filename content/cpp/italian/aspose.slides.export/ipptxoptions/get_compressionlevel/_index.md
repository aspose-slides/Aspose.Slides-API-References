---
title: get_CompressionLevel()
second_title: Riferimento API Aspose.Slides per C++
description: "Specifica il livello di compressione usato quando si salva il documento della presentazione. Il valore predefinito è CompressionLevel::Level6."
type: docs
weight: 79
url: /it/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() metodo

Specifica il livello di compressione usato quando si salva il documento della presentazione. Il valore predefinito è [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Osservazioni

Livelli di compressione più alti producono file più piccoli ma richiedono più tempo di elaborazione. Il rapporto di compressione effettivo dipende dal contenuto della presentazione.

Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Vedi anche

* Enum [CompressionLevel](../../compressionlevel/)
* Classe [IPptxOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)