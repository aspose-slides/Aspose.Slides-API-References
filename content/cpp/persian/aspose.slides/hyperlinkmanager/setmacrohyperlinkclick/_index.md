---
title: SetMacroHyperlinkClick()
second_title: مرجع API Aspose.Slides برای C++
description: پیوند ماکرو را هنگام کلیک تنظیم می‌کند.
type: docs
weight: 79
url: /fa/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) متد

تنظیم لینک ماکرو هنگام کلیک.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | نام ماکرو |

### مقدار بازگشت

[Hyperlink](../../hyperlink/) شیء [IHyperlink](../../ihyperlink/)
## توضیحات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IHyperlink](../../ihyperlink/)
* کلاس [String](../../../system/string/)
* کلاس [HyperlinkManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)