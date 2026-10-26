---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides için C++ API Referansı
description: Makro bağlantısını bir tıklama ile ayarlar.
type: docs
weight: 79
url: /tr/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) metodu

Makro bağlantısını bir tıklama üzerine ayarlar.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Makronun adı |

## Dönüş Değeri

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IHyperlink](../../ihyperlink/)
* Sınıf [String](../../../system/string/)
* Sınıf [HyperlinkManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)