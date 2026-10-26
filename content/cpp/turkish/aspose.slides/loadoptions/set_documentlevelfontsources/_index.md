---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides için C++ API Referansı
description: Sunumda kullanılacak dış yazı tipleri için kaynakları belirtir. Bu yazı tipleri, sunumun ömrü boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz
type: docs
weight: 222
url: /tr/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) metodu


Sunumda kullanılacak dış yazı tipleri için kaynakları belirtir. Bu yazı tipleri, sunumun ömrü boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
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
// sunumla çalış
// CustomFont1, CustomFont2 ve assets\\fonts & global\\fonts klasörlerinden ve alt klasörlerinden gelen yazı tipleri sunuma açıktır
```

## Diğer Bilgiler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontSources](../../ifontsources/)
* Sınıf [LoadOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)