---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda kullanılacak harici yazı tipleri için kaynakları belirtir. Bu yazı tipleri, sunumun ömrü boyunca sunuma açıktır ve diğer sunumlarla paylaşılmaz.
type: docs
weight: 209
url: /tr/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() metodu


Sunumda kullanılacak harici yazı tipleri için kaynakları belirtir. Bu yazı tipleri, sunumun ömrü boyunca sunuma açıktır ve diğer sunumlarla paylaşılmaz.

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Açıklamalar


Aşağıdaki örnek, PowerPoint [Presentation](../../presentation/) ile kullanılan özel yazı tiplerinin nasıl belirtileceğini gösterir.
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// sunum ile çalışın
// CustomFont1, CustomFont2 ve assets\fonts ve global\fonts klasörlerinden ve alt klasörlerinden gelen yazı tipleri sunuma açıktır
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontSources](../../ifontsources/)
* Sınıf [LoadOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)