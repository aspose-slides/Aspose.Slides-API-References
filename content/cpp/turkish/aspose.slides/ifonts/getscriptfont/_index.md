---
title: GetScriptFont()
second_title: Aspose.Slides için C++ API Referansı
description: Sunum temasından belirli bir script etiketine bağlı yazı tipi adını alır.
type: docs
weight: 92
url: /tr/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) yöntemi

Sunum temasından belirli bir script etiketine bağlı yazı tipi adını alır.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Yazı sistemini tanımlamak için kullanılan BCP-47 script kodu (örn., "Latn", "Cyrl", "Jpan"). |

### Dönüş Değeri

Belirtilen script için kullanılan yazı tipinin adı, script tanımlı değilse **null** döner.
## Açıklamalar

Bu örnek, sunum temasında Kiril scriptine atanmış yazı tipini nasıl alacağınızı gösterir. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [IFonts](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kitaplık [Aspose.Slides](../../../)