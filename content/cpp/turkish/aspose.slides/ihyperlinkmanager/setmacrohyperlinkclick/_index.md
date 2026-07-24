---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides for C++ API Referansı
description: Makro bağlantısını tıklama üzerine ayarlar.
type: docs
weight: 79
url: /tr/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) metod

Makro bağlantısını tıklama üzerine ayarlar.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Makronun adı |

### Dönüş Değeri

[Hyperlink](../../hyperlink/) nesne [IHyperlink](../../ihyperlink/)
## Açıklamalar

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IHyperlink](../../ihyperlink/)
* Sınıf [String](../../../system/string/)
* Sınıf [IHyperlinkManager](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)