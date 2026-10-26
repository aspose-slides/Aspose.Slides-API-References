---
title: set_RefreshThumbnail()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda bude miniatura prezentace obnovena. Zapisujte bool. Výchozí hodnota je true.
type: docs
weight: 66
url: /cs/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) metoda


Určuje, zda bude miniatura prezentace obnovena. Zapisujte **bool**. Výchozí hodnota je **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Poznámky


Když je hodnota možnosti **true**, bude vygenerována nová miniatura.

Když je hodnota možnosti **false**, aktuální miniatura bude uložena tak, jak je.

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Viz také

* Class [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)