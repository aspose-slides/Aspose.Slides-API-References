---
title: get_Placeholder()
second_title: Aspose.Slides برای C++ مرجع API
description: placeholder را برای یک شکل برمی‌گرداند. اگر شکل placeholder نداشته باشد مقدار null را برمی‌گرداند. فقط خواندنی IPlaceholder.
type: docs
weight: 14
url: /fa/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() متد


placeholder را برای یک شکل برمی‌گرداند. اگر شکل placeholder نداشته باشد، مقدار null را برمی‌گرداند. فقط خواندنی [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## نکات


مثال زیر نشان می‌دهد که چگونه Text را در [Placeholder](../../placeholder/). 
```cpp
// یک شیء از کلاس Presentation ایجاد می‌کند
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// به اولین اسلاید دسترسی پیدا می‌کند
auto slide = pres->get_Slides()->idx_get(0);

// از اشکال عبور می‌کند تا placeholder را پیدا کند
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // متن هر placeholder را تغییر می‌دهد
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// ارائه را روی دیسک ذخیره می‌کند
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 مثال زیر نشان می‌دهد که چگونه Prompt Text را در [Placeholder](../../placeholder/) تنظیم کنید. 
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

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPlaceholder](../../iplaceholder/)
* کلاس [Shape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)