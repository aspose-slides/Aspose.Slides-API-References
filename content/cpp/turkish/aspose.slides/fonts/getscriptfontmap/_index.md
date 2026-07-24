---
title: GetScriptFontMap()
second_title: Aspose.Slides C++ API Referansı
description: Sunumdaki tüm script font tanımlarının bir sözlüğünü döndürür.
type: docs
weight: 79
url: /tr/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() metod

Sunumdaki tüm script font tanımlarının bir sözlüğünü döndürür.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```

### Dönüş Değeri

Script kodlarını yazı tipi adlarıyla eşleyen bir sözlük.
## Açıklamalar

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDictionary](../../../system.collections.generic/idictionary/)
* Sınıf [String](../../../system/string/)
* Sınıf [Fonts](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)