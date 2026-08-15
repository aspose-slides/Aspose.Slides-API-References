---
title: get_Placeholder()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回形狀的佔位符。如果形狀沒有佔位符，則傳回 null。唯讀 IPlaceholder.
type: docs
weight: 14
url: /zh-hant/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() 方法


返回形狀的佔位符。如果形狀沒有佔位符，則返回 null。唯讀 [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## 備註


以下範例說明如何在 [Placeholder](../../placeholder/) 中變更 Text。
```cpp
// 實例化 Presentation 類別
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// 存取第一張投影片
auto slide = pres->get_Slides()->idx_get(0);

// 遍歷形狀以尋找佔位符
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // 更改每個佔位符中的文字
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// 將簡報儲存至磁碟
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 以下範例說明如何在 [Placeholder](../../placeholder/) 中設定 Prompt Text。
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

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPlaceholder](../../iplaceholder/)
* 類別 [Shape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)