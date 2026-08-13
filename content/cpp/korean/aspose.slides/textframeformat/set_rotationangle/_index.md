---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바운딩 박스 내 텍스트에 적용되는 회전을 사용자 지정하여 지정합니다. 지정되지 않은 경우, 해당 모양의 회전이 사용됩니다. 지정된 경우, 이는 모양과 독립적으로 적용됩니다. 즉, 모양에 회전이 적용되는 동시에 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성 및 속성 TextVerticalType에 정의된 수직 유형에서 요약된 시각적 텍스트 회전값이 결과로 제공됩니다. float 형식으로 기록합니다.
type: docs
weight: 313
url: /ko/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) 메서드

바운딩 박스 안의 텍스트에 적용되는 회전을 사용자 지정하여 지정합니다. 지정되지 않은 경우, 해당 모양의 회전이 사용됩니다. 지정된 경우, 이는 모양과 독립적으로 적용됩니다. 즉, 모양에 회전이 적용될 수 있으며 텍스트 자체에도 별도의 회전이 적용될 수 있습니다. 이 속성 및 속성 TextVerticalType의 미리 정의된 수직 유형에서 요약된 시각적 텍스트 회전값이 결과로 제공됩니다. **float** 형식으로 기록합니다.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## 비고

예를 들어, 모양에 시계 방향으로 90도 회전이 적용된 경우를 생각해 보십시오. 여기에 더해 텍스트 본문 자체에 반시계 방향으로 -90도 회전이 적용됩니다. 이렇게 되면 최종 모양은 회전된 것처럼 보이지만, 그 안의 텍스트는 회전되지 않은 것처럼 보입니다.

## 관련 내용

* 클래스 [TextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)