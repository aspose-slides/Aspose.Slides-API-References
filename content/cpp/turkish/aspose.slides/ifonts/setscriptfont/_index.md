---
title: SetScriptFont()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir script etiketine bir yazı tipi adı atar; bu, sunumda o scriptin metninin nasıl render edileceğini tanımlar.
type: docs
weight: 105
url: /tr/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) metodu

Belirli bir script etiketine bir yazı tipi adı atar; bu, sunumda o scriptin metninin nasıl render edileceğini tanımlar.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Yazı sistemini tanımlayan BCP-47 script kodu (örn. "Arab", "Hebr", "Hans"). |
| fontName | [System::String](../../../system/string/) | Belirtilen script için atanacak yazı tipi adı. |

## Notlar

Bu örnek, Arapça scripti için yazı tipini "Segoe UI" olarak nasıl ayarlayacağınızı gösterir:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [IFonts](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)