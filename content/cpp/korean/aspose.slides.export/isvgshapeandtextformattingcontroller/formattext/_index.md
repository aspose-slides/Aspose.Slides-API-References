---
title: FormatText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 함수는 SVG에 텍스트 부분을 렌더링하기 전에 호출되어 사용자가 결과 SVG를 제어할 수 있게 합니다.
type: docs
weight: 1
url: /ko/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) 메서드


이 함수는 SVG에 텍스트 부분을 렌더링하기 전에 호출되어 사용자가 결과 SVG를 제어할 수 있게 합니다.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | SVG tspan 생성을 제어하는 객체입니다. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | 소스 부분입니다. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | 소스 부분 텍스트 프레임입니다. |

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISvgTSpan](../../isvgtspan/)
* Class [IPortion](../../../aspose.slides/iportion/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [ISvgShapeAndTextFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)