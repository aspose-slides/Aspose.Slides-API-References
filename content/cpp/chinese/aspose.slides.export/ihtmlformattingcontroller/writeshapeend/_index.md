---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API 参考
description: 在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，当前幻灯片的图像生成将完成，已添加的 html 片段将被插入，并在之前的图像之上启动新的图像。
type: docs
weight: 66
url: /zh/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 方法

在 shape 渲染之前调用。每个 shape 调用一次。如果此函数向 generator 写入任何内容，当前幻灯片的图像生成将完成，已添加的 html 片段将被插入，并在之前的图像之上启动新的图像。

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 输出对象。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 是最后渲染的。 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IHtmlGenerator](../../ihtmlgenerator/)
* 类 [IShape](../../../aspose.slides/ishape/)
* 类 [IHtmlFormattingController](../)
* 命名空间 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)