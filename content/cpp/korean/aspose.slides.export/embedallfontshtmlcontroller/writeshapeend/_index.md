---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 도형이 렌더링되기 전에 호출됩니다. 각 도형마다 한 번 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 완료되고, 추가된 HTML 조각이 삽입되며 새로운 이미지가 이전 이미지 위에서 시작됩니다.
type: docs
weight: 79
url: /ko/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) 메서드

도형의 렌더링 전에 호출됩니다. 각 도형마다 한 번씩 호출됩니다. 이 함수가 generator에 무언가를 쓰면 현재 슬라이드 이미지 생성이 완료되고, 추가된 HTML 조각이 삽입되며 새로운 이미지가 이전 이미지 위에서 시작됩니다.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | 출력 객체. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) 마지막으로 렌더링되는. |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IHtmlGenerator](../../ihtmlgenerator/)
* 클래스 [IShape](../../../aspose.slides/ishape/)
* 클래스 [EmbedAllFontsHtmlController](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)