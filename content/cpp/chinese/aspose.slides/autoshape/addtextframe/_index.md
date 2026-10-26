---
title: AddTextFrame()
second_title: Aspose.Slides for C++ API 参考
description: 向形状添加一个新的 TextFrame。如果形状已经拥有 TextFrame，则仅更改其文本。
type: docs
weight: 66
url: /zh/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) 方法

向形状添加一个新的[TextFrame](../../textframe/)。如果形状已经有[TextFrame](../../textframe/)，则仅更改其文本。

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 新[TextFrame](../../textframe/)的默认文本。 |

## 备注

以下示例代码展示了如何在 PowerPoint [Presentation](../../presentation/) 中添加水印文本。
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
以下示例展示了如何在 [Slide](../../slide/) 上创建文本框。
```cpp
// 实例化 Presentation
auto pres = System::MakeObject<Presentation>();

// 获取演示文稿中的第一张幻灯片
auto slide = pres->get_Slides()->idx_get(0);
// 添加一个类型为 Rectangle 的 AutoShape
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// 向 Rectangle 添加 TextFrame
shape->AddTextFrame(u" ");
// 访问 TextFrame
auto txtFrame = shape->get_TextFrame();
// 为 TextFrame 创建 Paragraph 对象
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// 为段落创建 Portion 对象
auto portion = para->get_Portions()->idx_get(0);
// 设置文本
portion->set_Text(u"Aspose TextBox");
// 将演示文稿保存到磁盘
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何在文本框中添加列。
```cpp
auto presentation = System::MakeObject<Presentation>();

// 获取演示文稿中的第一张幻灯片
auto slide = presentation->get_Slides()->idx_get(0);
// 添加一个类型为 Rectangle 的 AutoShape
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// 向 Rectangle 添加 TextFrame
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// 获取 TextFrame 的文本格式
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// 指定 TextFrame 中的列数
format->set_ColumnCount(3);
// 指定列之间的间距
format->set_ColumnSpacing(10);
// 保存演示文稿
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ITextFrame](../../itextframe/)
* 类 [String](../../../system/string/)
* 类 [AutoShape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)