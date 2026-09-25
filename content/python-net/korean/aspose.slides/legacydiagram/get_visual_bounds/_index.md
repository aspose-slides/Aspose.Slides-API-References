---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계를 가져옵니다.

### 반환
[`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)는 도형의 시각적 경계를 나타내는 객체이며,
             슬라이드 좌표계에 해당합니다.



```python
def get_visual_bounds(self):
    ...
```


### 비고
반환된 사각형은 슬라이드 좌표계에서 렌더링되는 동안 도형이 생성한 모든 콘텐츠의 축에 정렬된 경계를 나타냅니다.
             
이 경계는 도형의 모델 경계([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))와 다를 수 있으며, 렌더링된 콘텐츠가 슬라이드 원점을 넘어 확장될 경우 음수 좌표를 포함할 수 있습니다.
             
시각적 경계는 변환(예: 회전), 선 두께 및 연결, 텍스트 레이아웃 및 오버플로우, SmartArt 기하학, 그리고 도형의 최종 렌더링 모습을 영향을 주는 기타 레이아웃 효과와 같은 렌더링 관련 요소들을 고려합니다.
             
반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.



### 참고
* 클래스 [`LegacyDiagram`](/slides/python-net/ko/aspose.slides/legacydiagram)
* 클래스 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)