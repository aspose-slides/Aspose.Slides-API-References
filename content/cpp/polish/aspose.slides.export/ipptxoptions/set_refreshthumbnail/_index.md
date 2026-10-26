---
title: set_RefreshThumbnail()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Określa, czy miniatura prezentacji ma zostać odświeżona. Zapisz bool. Domyślna wartość to true.
type: docs
weight: 66
url: /pl/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) metoda


Określa, czy miniatura prezentacji ma zostać odświeżona. Zapisz **bool**. Domyślna wartość to **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Uwagi


Gdy wartość opcji jest **true**, nowa miniatura zostanie wygenerowana.

Gdy wartość opcji jest **false**, bieżąca miniatura zostanie zachowana w niezmienionej postaci.

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