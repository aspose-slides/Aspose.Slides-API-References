---
title: set_RefreshThumbnail()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa, czy miniatura prezentacji zostanie odświeżona. Zapisz bool. Domyślna wartość to true.
type: docs
weight: 66
url: /pl/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) metoda

Określa, czy miniatura prezentacji zostanie odświeżona. Zapisz **bool**. Domyślna wartość to **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
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