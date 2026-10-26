---
title: get_Placeholder()
second_title: مرجع API Aspose.Slides لـ C++
description: يعيد العنصر النائب للشكل. يعيد null إذا لم يكن للشكل عنصر نائب. للقراءة فقط IPlaceholder.
type: docs
weight: 14
url: /ar/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() طريقة

يعيد العنصر النائب للشكل. يعيد null إذا لم يكن للشكل عنصر نائب. للقراءة فقط [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## ملاحظات

المثال التالي يوضح كيفية تغيير النص في [Placeholder](../../placeholder/).
```cpp
// إنشاء كائن من فئة Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// الوصول إلى الشريحة الأولى
auto slide = pres->get_Slides()->idx_get(0);

// التكرار عبر الأشكال للعثور على العنصر النائب
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // تغيير النص في كل عنصر نائب
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// حفظ العرض التقديمي إلى القرص
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
المثال التالي يوضح كيفية ضبط نص المطالبة في [Placeholder](../../placeholder/).
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation2.pptx");

auto slide = pres->get_Slides()->idx_get(0);
for (auto&& shape : slide->get_Slide()->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr && System::ObjectExt::Is<AutoShape>(shape))
    {
        System::String text = u"";
        if (shape->get_Placeholder()->get_Type() == PlaceholderType::CenteredTitle)
        {
            text = u"Add Title";
        }
        else if (shape->get_Placeholder()->get_Type() == PlaceholderType::Subtitle)
        {
            text = u"Add Subtitle";
        }

        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(text);

        System::Console::WriteLine(System::String::Format(u"Placeholder with text: {0}", text));
    }
}

pres->Save(u"Placeholders_PromptText.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPlaceholder](../../iplaceholder/)
* فئة [Shape](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)