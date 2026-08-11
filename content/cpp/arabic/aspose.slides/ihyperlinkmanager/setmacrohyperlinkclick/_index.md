---
title: SetMacroHyperlinkClick()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: تعيين ارتباط ماكرو عند النقر.
type: docs
weight: 79
url: /ar/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) طريقة

تعيين ارتباط ماكرو على النقر.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | اسم الماكرو |

### قيمة الإرجاع

[Hyperlink](../../hyperlink/) كائن [IHyperlink](../../ihyperlink/)

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IHyperlink](../../ihyperlink/)
* فئة [String](../../../system/string/)
* فئة [IHyperlinkManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)