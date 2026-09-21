---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠로부터 계산된 모양의 시각적 경계를 가져옵니다.

### 반환
슬라이드 좌표계에서 모양의 시각적 경계를 나타내는 **aspose.slides.RectangleF**입니다.


```python
def get_visual_bounds(self):
    ...
```


### 비고
반환된 사각형은 슬라이드 좌표 공간에서 렌더링 중 모양에 의해 생성된 모든 콘텐츠의 축에 정렬된 경계를 나타냅니다.
             
이러한 경계는 모양의 모델 경계([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))와 다를 수 있으며, 렌더링된 콘텐츠가 슬라이드 원점을 벗어나면 음수 좌표를 포함할 수 있습니다.
             
시각적 경계는 변환(예: 회전), 스트로크 너비와 조인, 텍스트 레이아웃 및 오버플로우, SmartArt 기하, 그리고 모양의 최종 렌더링 모습에 영향을 주는 기타 레이아웃 효과와 같이 렌더링 관련 요소들을 고려합니다.
             
반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.


### 참조
* 클래스 [`Ink`](/slides/python-net/ko/aspose.slides.ink/ink)
* 모듈 [`aspose.slides.ink`](/slides/python-net/ko/aspose.slides.ink)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)