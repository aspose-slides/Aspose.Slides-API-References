---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides للـ C++ مرجع API
description: تعيين ارتباط ماكرو عند النقر.
type: docs
weight: 79
url: /ar/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) طريقة


تعيين ارتباط ماكرو عند النقر.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | اسم الماكرو |

### قيمة الإرجاع

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IHyperlink](../../ihyperlink/)
* فئة [String](../../../system/string/)
* فئة [HyperlinkManager](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)