---
title: get_Placeholder()
second_title: Aspose.Slides C++ API 参考
description: 返回形状的占位符。如果形状没有占位符，则返回 null。只读 IPlaceholder.
type: docs
weight: 14
url: /zh/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() method

返回形状的占位符。如果形状没有占位符，则返回 null。只读 [IPlaceholder](../../iplaceholder/)。

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## 备注

以下示例展示了如何在 [Placeholder](../../placeholder/) 中更改 Text。 
```cpp
// 实例化一个 Presentation 类
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// 访问第一张幻灯片
auto slide = pres->get_Slides()->idx_get(0);

// 遍历形状以查找占位符
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // 更改每个占位符中的文本
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// 将演示文稿保存到磁盘
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 以下示例展示了如何在 [Placeholder](../../placeholder/) 中设置 Prompt Text。 
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

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPlaceholder](../../iplaceholder/)
* 类 [Shape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)