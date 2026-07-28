---
title: get_RefreshThumbnail()
second_title: Aspose.Slides dla C++ – Referencja API
description: Określa, czy miniatura prezentacji zostanie odświeżona. Odczyt bool. Domyślna wartość to true.
type: docs
weight: 53
url: /pl/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() metoda

Określa, czy miniatura prezentacji zostanie odświeżona. Odczyt **bool**. Domyślna wartość to **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Uwagi

Gdy wartość opcji jest **true**, nowa miniatura zostanie wygenerowana.

Gdy wartość opcji jest **false**, bieżąca miniatura zostanie zapisana w niezmienionej formie.

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zobacz także

* Klasa [PptxOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)