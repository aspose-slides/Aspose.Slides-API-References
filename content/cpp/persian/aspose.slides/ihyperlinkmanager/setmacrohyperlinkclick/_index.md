---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides برای C++ مستندات API
description: تنظیم پیوند ماکرو هنگام کلیک.
type: docs
weight: 79
url: /fa/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) متد


تنظیم پیوند ماکرو هنگام کلیک.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | نام ماکرو |

### مقدار بازگشت

[Hyperlink](../../hyperlink/) شی [IHyperlink](../../ihyperlink/)
## توضیحات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## موارد مرتبط

* تایپ‌دِف [SharedPtr](../../../system/sharedptr/)
* کلاس [IHyperlink](../../ihyperlink/)
* کلاس [String](../../../system/string/)
* کلاس [IHyperlinkManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)