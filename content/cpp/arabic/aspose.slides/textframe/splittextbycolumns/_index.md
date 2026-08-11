---
title: SplitTextByColumns()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقسم محتوى النص في ITextFrame إلى مصفوفة من السلاسل، حيث يطابق كل عنصر عمود نص منفصل داخل الإطار.
type: docs
weight: 144
url: /ar/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() طريقة

يقسّم محتوى النص في [ITextFrame](../../itextframe/) إلى مصفوفة من السلاسل، 
 حيث يطابق كل عنصر عمود نص منفصل داخل الإطار.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### قيمة الإرجاع

مصفوفة من السلاسل، حيث تمثّل كل سلسلة محتوى النص لعمود محدد في [ITextFrame](../../itextframe/).

## ملاحظات

إذا لم يحتوي إطار النص على أعمدة متعددة، فإن المصفوفة المرتجعة ستحوي عنصراً واحداً يحتوي على النص الكامل. 
 الأعمدة الفارغة ستُمثَّل كسلاسل فارغة في المصفوفة. 
المثال التالي يوضح كيفية استخدام [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// احصل على الشكل الأول على الشريحة وحوله إلى ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// قسم محتوى إطار النص إلى أعمدة
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// اطبع نص كل عمود إلى وحدة التحكم
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [TextFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)