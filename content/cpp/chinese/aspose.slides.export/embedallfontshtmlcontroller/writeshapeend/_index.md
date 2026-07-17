---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API 参考
description: 在形状渲染之前调用。对每个形状调用一次。如果此函数向生成器写入任何内容，当前幻灯片图像的生成将完成，添加的 html 片段将被插入，并将在前一个图像之上启动新的图像。
type: docs
weight: 79
url: /zh/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 方法

在 shape 的渲染之前调用。对每个 shape 调用一次。如果此函数向 generator 写入任何内容，则当前幻灯片图像生成将完成，添加的 html 片段将被插入，并将在前一个图像之上启动新的图像。

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 输出对象。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 最后渲染。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IHtmlGenerator](../../ihtmlgenerator/)
* 类 [IShape](../../../aspose.slides/ishape/)
* 类 [EmbedAllFontsHtmlController](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)