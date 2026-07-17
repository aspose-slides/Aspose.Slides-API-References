---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API 参考
description: 在形状渲染之前调用。对每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片的图像生成将完成，插入添加的 html 片段，并在之前的图像之上开始生成新图像。
type: docs
weight: 53
url: /zh/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 方法

在形状渲染之前调用。对每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片的图像生成将完成，插入添加的 html 片段，并在之前的图像之上开始生成新图像。

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 输出对象。 |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 即将渲染。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IHtmlGenerator](../../ihtmlgenerator/)
* 类 [IShape](../../../aspose.slides/ishape/)
* 类 [IHtmlFormattingController](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)