---
title: SplitTextByColumns()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقسم محتوى النص في ITextFrame إلى مصفوفة من السلاسل، حيث يطابق كل عنصر عمود نص منفصل داخل الإطار.
type: docs
weight: 118
url: /ar/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() طريقة

يقسم محتوى النص في [ITextFrame](../) إلى مصفوفة من السلاسل، حيث يطابق كل عنصر عمود نص منفصل داخل الإطار.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```

### قيمة الإرجاع

مصفوفة من السلاسل، حيث تمثل كل سلسلة محتوى النص لعمود محدد في [ITextFrame](../).

## ملاحظات

إذا لم يحتوي إطار النص على أعمدة متعددة، فستحتوي المصفوفة المعادة على عنصر واحد فقط يحتوي على النص الكامل.

ستُمثَّل الأعمدة الفارغة كسلاسل فارغة في المصفوفة.

المثال التالي يوضح كيفية استخدام [ITextFrame::SplitTextByColumns](./):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Get the first shape on the slide and cast it to ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Split the text frame content into columns
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print each column's text to the console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [ITextFrame](../)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)