---
title: get_RefreshThumbnail()
second_title: Aspose.Slides pro C++ API Reference
description: Specifikuje, zda bude miniatura prezentace aktualizována. Čtení bool. Výchozí hodnota je true.
type: docs
weight: 53
url: /cs/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() metoda

Určuje, zda bude miniatura prezentace aktualizována. Čtení **bool**. Výchozí hodnota je **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## Poznámky

Když je hodnota volby **true**, bude vygenerována nová miniatura.

Když je hodnota volby **false**, bude aktuální miniatura uložena tak, jak je.

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Viz také

* Třída [IPptxOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)