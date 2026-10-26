---
title: SplitTextByColumns()
second_title: Aspose.Slides برای C++ مرجع API
description: محتوای متنی ITextFrame را به آرایه‌ای از رشته‌ها تقسیم می‌کند که هر عنصر متناظر با یک ستون متن جداگانه در داخل فریم است.
type: docs
weight: 144
url: /fa/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() متد

محتوای متنی [ITextFrame](../../itextframe/) را به آرایه‌ای از رشته‌ها تقسیم می‌کند،
 که هر عنصر متناظر با یک ستون متن جداگانه در داخل فریم است.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### مقدار بازگشتی

آرایه‌ای از رشته‌ها، که هر رشته محتوای متنی یک ستون خاص را
 در [ITextFrame](../../itextframe/) نمایش می‌دهد.

## توضیحات

اگر فریم متن حاوی چندین ستون نباشد، آرایهٔ بازگشتی یک عنصر واحد خواهد داشت 
 که شامل تمام متن است.

 ستون‌های خالی به عنوان رشته‌های خالی در آرایه نمایش داده می‌شوند.
مثال زیر نشان می‌دهد چطور از [TextFrame::SplitTextByColumns](./) استفاده شود: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// دریافت اولین شکل در اسلاید و تبدیل آن به ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// تقسیم محتوای فریم متن به ستون‌ها
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// چاپ متن هر ستون در کنسول
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)