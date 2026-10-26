---
title: get_RefreshThumbnail()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje, zda bude náhled prezentace aktualizován. Vrací bool. Výchozí hodnota je true.
type: docs
weight: 53
url: /cs/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() metoda

Určuje, zda bude náhled prezentace aktualizován. Vrací **bool**. Výchozí hodnota je **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Poznámky

Když je hodnota volby **true**, bude vygenerován nový náhled.

Když je hodnota volby **false**, bude aktuální náhled uložen tak, jak je.

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Viz také

* Třída [PptxOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)