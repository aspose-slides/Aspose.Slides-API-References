---
title: RemoveScriptFont()
second_title: Aspose.Slides için C++ API Referansı
description: Tema font koleksiyonundan belirli bir script etiketine ilişkin font ayarını kaldırır.
type: docs
weight: 118
url: /tr/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) yöntemi

Temanın font koleksiyonundan belirli bir script etiketine ilişkin font ayarını kaldırır.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Font ayarının kaldırılması gereken BCP-47 script kodu. |

## Açıklamalar

Bu örnek, İbranice scripti için font eşlemesini nasıl kaldıracağınızı gösterir: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [Fonts](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)