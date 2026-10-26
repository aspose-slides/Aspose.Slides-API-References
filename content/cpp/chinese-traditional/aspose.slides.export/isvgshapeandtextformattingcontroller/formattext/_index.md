---
title: FormatText()
second_title: Aspose.Slides for C++ API 參考文件
description: 此函式會在將文字部分渲染為 SVG 之前被呼叫，以允許使用者控制產生的 SVG。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) 方法


此函式會在將文字部分渲染為 SVG 之前被呼叫，以允許使用者控制產生的 SVG。

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | 用於控制 SVG tspan 生成的物件。 |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | 來源部分。 |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | 來源部分的文字框。 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISvgTSpan](../../isvgtspan/)
* 類別 [IPortion](../../../aspose.slides/iportion/)
* 類別 [ITextFrame](../../../aspose.slides/itextframe/)
* 類別 [ISvgShapeAndTextFormattingController](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)