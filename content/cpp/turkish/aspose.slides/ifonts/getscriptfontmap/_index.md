---
title: GetScriptFontMap()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda bulunan tüm betik yazı tipi tanımlarının bir sözlüğünü döndürür.
type: docs
weight: 79
url: /tr/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() yöntemi


Sunumdaki tüm betik yazı tipi tanımlarının bir sözlüğünü döndürür.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### Dönüş Değeri

Betik kodlarını yazı tipi adlarına eşleyen bir sözlük.
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
* Sınıf [IFonts](../)
* İsim alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)