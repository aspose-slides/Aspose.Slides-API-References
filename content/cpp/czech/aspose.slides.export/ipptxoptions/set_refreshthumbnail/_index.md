---
title: set_RefreshThumbnail()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda bude miniaturka prezentace aktualizována. Zapište bool. Výchozí hodnota je true.
type: docs
weight: 66
url: /cs/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) metoda

Určuje, zda bude miniaturka prezentace aktualizována. Zapište **bool**. Výchozí hodnota je **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Poznámky

Když je hodnota možnosti **true**, bude vygenerována nová miniatura.

Když je hodnota možnosti **false**, bude aktuální miniatura uložena beze změny.

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