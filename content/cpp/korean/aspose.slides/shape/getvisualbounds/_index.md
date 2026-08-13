---
title: GetVisualBounds()
second_title: Aspose.Slides for C++ API 참조
description: 렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계를 가져옵니다.
type: docs
weight: 677
url: /ko/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() 메서드

렌더링된 콘텐츠를 기준으로 계산된 도형의 시각적 경계를 가져옵니다.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### 반환 값

슬라이드 좌표계에서 도형의 시각적 경계를 나타내는 [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)입니다.

## 비고

반환된 사각형은 슬라이드 좌표 공간에서 렌더링 중 도형에 의해 생성된 모든 콘텐츠의 축 정렬 경계를 나타냅니다.

이 경계는 도형의 모델 경계([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../))와 다를 수 있으며, 렌더링된 콘텐츠가 슬라이드 원점을 벗어날 경우 음수 좌표를 포함할 수 있습니다.

시각적 경계는 변환(예: 회전), 스트로크 두께 및 연결, 텍스트 레이아웃 및 오버플로우, [SmartArt](../../../aspose.slides.smartart/) 기하학 및 도형의 최종 렌더링 모습에 영향을 주는 기타 레이아웃 효과와 같은 렌더링 관련 요소를 고려합니다.

반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.

## 참조

* 클래스 [RectangleF](../../../system.drawing/rectanglef/)
* 클래스 [Shape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)