---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API 참조
description: 경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. 지정되지 않은 경우, 함께 있는 도형의 회전이 사용됩니다. 지정된 경우, 이는 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용되는 동시에 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 정의된 사전 정의 수직 유형을 종합하여 시각적 텍스트 회전값이 결정됩니다. float 형식으로 작성합니다.
type: docs
weight: 352
url: /ko/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) 메서드


경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. 지정되지 않은 경우, 함께 있는 도형의 회전이 사용됩니다. 지정된 경우, 이는 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용되는 동시에 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 정의된 사전 설정 수직 유형을 종합하여 시각적 텍스트 회전값이 결정됩니다. **float** 형식으로 작성합니다.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## 비고


예를 들어, 도형에 시계 방향으로 90도 회전이 적용된 경우를 생각해 보십시오. 여기에 더해 텍스트 본문 자체에도 반시계 방향으로 -90도 회전이 적용됩니다. 이렇게 되면 결과 도형은 회전된 것처럼 보이지만, 그 안의 텍스트는 전혀 회전되지 않은 것처럼 보입니다. 

## 참고

* 클래스 [ITextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)