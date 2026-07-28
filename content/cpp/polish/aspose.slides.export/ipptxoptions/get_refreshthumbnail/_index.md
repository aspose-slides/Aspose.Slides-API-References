---
title: get_RefreshThumbnail()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Określa, czy miniatura prezentacji zostanie odświeżona. Odczyt bool. Domyślna wartość to true.
type: docs
weight: 53
url: /pl/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() metoda


Określa, czy miniatura prezentacji zostanie odświeżona. Odczyt **bool**. Domyślna wartość to **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## Uwagi


Gdy wartość opcji jest **true**, zostanie wygenerowana nowa miniatura.

Gdy wartość opcji jest **false**, bieżąca miniatura zostanie zapisana w niezmienionej formie.

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zobacz także

* Klasa [IPptxOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)