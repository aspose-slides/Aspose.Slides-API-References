---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바운딩 박스 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우, 함께 있는 shape의 회전이 사용됩니다. 지정된 경우, 이는 shape와 독립적으로 적용됩니다. 즉, shape에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용될 수 있습니다. 이 property와 property TextVerticalType에 정의된 사전 정의된 수직 유형을 종합한 시각적 텍스트 회전값이 결과값으로 제공합니다. Read float.
type: docs
weight: 339
url: /ko/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() 메서드


바운딩 박스 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우, 함께 있는 도형의 회전이 사용됩니다. 지정된 경우, 이는 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 정의된 수직 유형을 종합한 시각적 텍스트 회전값이 결과값으로 제공됩니다. **float** 형식으로 읽습니다.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## 비고


도형에 시계 방향으로 90도 회전이 적용된 경우를 생각해 보십시오. 여기에 텍스트 본문 자체에 반시계 방향으로 -90도 회전이 적용됩니다. 그러면 결과 도형은 회전된 것처럼 보이지만 그 안의 텍스트는 전혀 회전되지 않은 것처럼 보입니다. 
## 참조

* 클래스 [ITextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)