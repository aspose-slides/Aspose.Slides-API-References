---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경계 상자 내부 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우, 해당 모양의 회전이 사용됩니다. 지정된 경우, 모양과는 별도로 적용됩니다. 즉, 모양에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 별도로 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 미리 정의된 수직 유형을 종합한 시각적 텍스트 회전값이 결과로 반환됩니다. float 형식.
type: docs
weight: 235
url: /ko/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() 메서드

텍스트가 경계 상자 안에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우, 해당 모양의 회전이 사용됩니다. 지정된 경우, 모양과는 별도로 적용됩니다. 즉, 모양에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 별도로 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 미리 정의된 수직 유형을 종합한 시각적 텍스트 회전값이 결과로 반환됩니다. **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## 비고

모양에 시계 방향으로 90도 회전이 적용된 경우를 고려하십시오. 추가로 텍스트 본문 자체에 반시계 방향으로 -90도 회전이 적용됩니다. 그러면 결과 모양은 회전된 것으로 보이지만 그 안의 텍스트는 전혀 회전되지 않은 것처럼 보입니다.

## 참조

* 클래스 [IChartTextBlockFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)