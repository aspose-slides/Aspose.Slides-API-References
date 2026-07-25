---
title: AddTextFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 図形に新しい TextFrame を追加します。図形に既に TextFrame がある場合は、単にそのテキストを変更します。
type: docs
weight: 66
url: /ja/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) メソッド


図形に新しい[TextFrame](../../textframe/)を追加します。図形に既に[TextFrame](../../textframe/)がある場合は、単にそのテキストを変更します。

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新しい[TextFrame](../../textframe/)のデフォルトテキスト。 |
## 備考



以下のサンプルコードは、PowerPoint [Presentation](../../presentation/)で透かしテキストを追加する方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 以下の例は、[Slide](../../slide/)上にテキストボックスを作成する方法を示しています。 
```cpp
// Presentation をインスタンス化します
auto pres = System::MakeObject<Presentation>();

// プレゼンテーションの最初のスライドを取得します
auto slide = pres->get_Slides()->idx_get(0);
// タイプを Rectangle に設定した AutoShape を追加します
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Rectangle に TextFrame を追加します
shape->AddTextFrame(u" ");
// テキストフレームにアクセスします
auto txtFrame = shape->get_TextFrame();
// テキストフレーム用の Paragraph オブジェクトを作成します
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Paragraph 用の Portion オブジェクトを作成します
auto portion = para->get_Portions()->idx_get(0);
// テキストを設定します
portion->set_Text(u"Aspose TextBox");
// プレゼンテーションをディスクに保存します
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 以下の例は、テキストボックスに列を追加する方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>();

// プレゼンテーションの最初のスライドを取得します
auto slide = presentation->get_Slides()->idx_get(0);
// タイプを Rectangle に設定した AutoShape を追加します
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Rectangle に TextFrame を追加します
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// TextFrame のテキスト形式を取得します
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// TextFrame の列数を指定します
format->set_ColumnCount(3);
// 列間の間隔を指定します
format->set_ColumnSpacing(10);
// プレゼンテーションを保存します
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../itextframe/)
* Class [String](../../../system/string/)
* Class [AutoShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)