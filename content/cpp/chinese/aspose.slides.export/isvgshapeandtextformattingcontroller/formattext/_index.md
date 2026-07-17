---
title: FormatText()
second_title: Aspose.Slides for C++ API 参考
description: 此函数在将文本部分渲染为 SVG 之前调用，以便用户控制生成的 SVG。
type: docs
weight: 1
url: /zh/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) 方法

此函数在将文本部分渲染为 SVG 之前调用，以便用户控制生成的 SVG。

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | 用于控制 SVG tspan 生成的对象。 |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | 来源部分。 |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | 来源部分的文本框。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISvgTSpan](../../isvgtspan/)
* 类 [IPortion](../../../aspose.slides/iportion/)
* 类 [ITextFrame](../../../aspose.slides/itextframe/)
* 类 [ISvgShapeAndTextFormattingController](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)