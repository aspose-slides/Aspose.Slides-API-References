---
title: get_Placeholder()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は null を返します。読み取り専用 IPlaceholder.
type: docs
weight: 14
url: /ja/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() メソッド

シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は null を返します。読み取り専用 [IPlaceholder](../../iplaceholder/)。

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## 備考

次の例は、[Placeholder](../../placeholder/) のテキストを変更する方法を示しています。 
```cpp
// Presentation クラスのインスタンスを生成します
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// 最初のスライドにアクセスします
auto slide = pres->get_Slides()->idx_get(0);

// プレースホルダーを探すためにシェイプを反復処理します
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // 各プレースホルダーのテキストを変更します
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// プレゼンテーションをディスクに保存します
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
次の例は、[Placeholder](../../placeholder/) でプロンプトテキストを設定する方法を示しています。 
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

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPlaceholder](../../iplaceholder/)
* クラス [Shape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)