---
title: SetScriptFont()
second_title: Aspose.Slides için C++ API Referansı
description: Belirli bir script etiketine bir yazı tipi adı atar; bu, o scriptin metninin sunumda nasıl görüntüleneceğini tanımlar.
type: docs
weight: 105
url: /tr/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) metodu

Belirli bir script etiketine bir yazı tipi adı atar; bu, o scriptin metninin sunumda nasıl görüntüleneceğini belirler.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 script kodu (örn., "Arab", "Hebr", "Hans") yazı sistemini tanımlar. |
| fontName | [System::String](../../../system/string/) | Belirtilen script için atanacak yazı tipi adı. |
## Açıklamalar

Bu örnek, Arapça scripti için yazı tipini "Segoe UI" olarak nasıl ayarlayacağınızı gösterir:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [Fonts](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)