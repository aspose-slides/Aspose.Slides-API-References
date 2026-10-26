---
title: AddTextFrame()
second_title: Aspose.Slides for C++ API 參考
description: 將新的 TextFrame 新增至圖形。如果圖形已經有 TextFrame，則僅更改其文字。
type: docs
weight: 66
url: /zh-hant/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) 方法

將新的 [TextFrame](../../textframe/) 新增到圖形中。如果圖形已經有 [TextFrame](../../textframe/)，則僅更改其文字。

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新 [TextFrame](../../textframe/) 的預設文字。 |

## 備註

以下範例程式碼展示如何在 PowerPoint [Presentation](../../presentation/) 中加入浮水印文字。 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
以下範例說明如何在 [Slide](../../slide/) 上建立文字方塊。 
```cpp
// 實例化 Presentation
auto pres = System::MakeObject<Presentation>();

// 取得簡報中的第一張投影片
auto slide = pres->get_Slides()->idx_get(0);
// 新增一個 AutoShape，類型設為 Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// 為 Rectangle 新增 TextFrame
shape->AddTextFrame(u" ");
// 取得文字框
auto txtFrame = shape->get_TextFrame();
// 為文字框建立 Paragraph 物件
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// 為段落建立 Portion 物件
auto portion = para->get_Portions()->idx_get(0);
// 設定文字
portion->set_Text(u"Aspose TextBox");
// 將簡報儲存至磁碟
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
以下範例說明如何在文字方塊中加入欄。 
```cpp
auto presentation = System::MakeObject<Presentation>();

// 取得簡報中的第一張投影片
auto slide = presentation->get_Slides()->idx_get(0);
// 新增一個 AutoShape，類型設為 Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// 為 Rectangle 新增 TextFrame
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// 取得 TextFrame 的文字格式
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// 指定 TextFrame 中的欄位數量
format->set_ColumnCount(3);
// 指定欄位之間的間距
format->set_ColumnSpacing(10);
// 儲存簡報
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ITextFrame](../../itextframe/)
* 類別 [String](../../../system/string/)
* 類別 [AutoShape](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)