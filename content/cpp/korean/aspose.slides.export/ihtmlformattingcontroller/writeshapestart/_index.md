---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API 참조
description: shape가 렌더링되기 전에 호출됩니다. 각 shape마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 완료되고, 추가된 html 조각이 삽입되며, 새로운 이미지가 이전 이미지 위에서 시작됩니다.
type: docs
weight: 53
url: /ko/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 메서드

shape의 렌더링 전에 호출됩니다. 각 shape마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 완료되고, 추가된 html 조각이 삽입되며, 새로운 이미지가 이전 이미지 위에서 시작됩니다.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 출력 객체. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 렌더링하려는. |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IHtmlGenerator](../../ihtmlgenerator/)
* 클래스 [IShape](../../../aspose.slides/ishape/)
* 클래스 [IHtmlFormattingController](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)