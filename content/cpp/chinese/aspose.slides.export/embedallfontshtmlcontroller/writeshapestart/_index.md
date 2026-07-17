---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API 参考
description: 在形状渲染之前调用。每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。
type: docs
weight: 66
url: /zh/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 方法

在形状渲染之前调用。每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像生成将结束，插入添加的 HTML 片段，并在之前的图像之上开始新的图像。

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 输出对象。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 即将渲染。 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IHtmlGenerator](../../ihtmlgenerator/)
* 类 [IShape](../../../aspose.slides/ishape/)
* 类 [EmbedAllFontsHtmlController](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)