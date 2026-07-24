---
title: RemoveScriptFont()
second_title: Aspose.Slides için C++ API Referansı
description: Tema font koleksiyonundaki belirli bir script etiketiyle ilişkili font ayarını kaldırır.
type: docs
weight: 118
url: /tr/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) yöntemi

Temanın font koleksiyonundaki belirli bir script etiketine bağlı font ayarını kaldırır.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Font ayarının kaldırılması gereken BCP-47 script kodu. |
## Açıklamalar

Bu örnek, İbranice betiği için font eşlemesini nasıl kaldıracağını gösterir: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [IFonts](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)