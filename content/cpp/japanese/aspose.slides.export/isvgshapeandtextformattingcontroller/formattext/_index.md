---
title: FormatText()
second_title: Aspose.Slides for C++ API リファレンス
description: この関数は、テキスト部分を SVG にレンダリングする前に呼び出され、ユーザーが生成される SVG を制御できるようにします。
type: docs
weight: 1
url: /ja/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) メソッド


この関数は、テキスト部分を SVG にレンダリングする前に呼び出され、ユーザーが生成される SVG を制御できるようにします。

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | SVG tspan の生成を制御するオブジェクト。 |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | ソース部分。 |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | ソース部分のテキストフレーム。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISvgTSpan](../../isvgtspan/)
* クラス [IPortion](../../../aspose.slides/iportion/)
* クラス [ITextFrame](../../../aspose.slides/itextframe/)
* クラス [ISvgShapeAndTextFormattingController](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)