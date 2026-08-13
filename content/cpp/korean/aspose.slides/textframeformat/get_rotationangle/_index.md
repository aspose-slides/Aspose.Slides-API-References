---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트가 경계 상자 내에 적용되는 회전을 사용자 지정으로 지정합니다. 지정되지 않은 경우, 해당 도형의 회전이 사용됩니다. 지정된 경우, 이 회전은 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용된 상태에서 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 미리 정의된 수직 유형을 기반으로 요약된 시각적 텍스트 회전의 최종 값이 제공됩니다. 읽기 float.
type: docs
weight: 300
url: /ko/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() 메서드


텍스트가 경계 상자 내에 적용되는 회전을 사용자 지정으로 지정합니다. 지정되지 않은 경우, 해당 도형의 회전이 사용됩니다. 지정된 경우, 이 회전은 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용된 상태에서 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 미리 정의된 수직 유형을 기반으로 요약된 시각적 텍스트 회전의 최종 값이 제공됩니다. 읽기 **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## 비고


도형에 시계 방향으로 90도 회전이 적용된 경우를 고려해 보십시오. 여기에 더해 텍스트 본문 자체에도 반시계 방향으로 -90도 회전이 적용됩니다. 그러면 최종 도형은 회전된 것으로 보이지만, 그 안의 텍스트는 전혀 회전되지 않은 것처럼 보이게 됩니다. 
## 참고

* 클래스 [TextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)