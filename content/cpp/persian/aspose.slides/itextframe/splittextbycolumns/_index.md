---
title: SplitTextByColumns()
second_title: مرجع API Aspose.Slides برای C++
description: محتواى متنی ITextFrame را به یک آرایه از رشته‌ها تقسیم می‌کند، به طوری که هر عنصر متناظر با یک ستون متنی جداگانه درون فریم باشد.
type: docs
weight: 118
url: /fa/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() متد


محتویات متنی [ITextFrame](../) را به یک آرایه از رشته‌ها تقسیم می‌کند،
 که هر عنصر متناظر با یک ستون متنی جداگانه در داخل فریم است.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### مقدار برگشت

یک آرایه از رشته‌ها، که هر رشته محتوای متنی یک ستون خاص را در [ITextFrame](../) نمایش می‌دهد.

## نکات

اگر فریم متن شامل چندین ستون نباشد، آرایهٔ بازگشتی تنها یک عنصر خواهد داشت که شامل تمام متن است.
ستون‌های خالی به عنوان رشته‌های خالی در آرایه نمایش داده می‌شوند.
مثال زیر نشان می‌دهد که چگونه از [ITextFrame::SplitTextByColumns](./) استفاده می‌شود:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// اولین شکل در اسلاید را دریافت کرده و به ITextFrame تبدیل می‌کند
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// محتویات فریم متن را به ستون‌ها تقسیم می‌کند
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// متن هر ستون را در کنسول چاپ می‌کند
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## مشاهده نیز

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [ITextFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)