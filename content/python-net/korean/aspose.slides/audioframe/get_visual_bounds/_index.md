---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계 영역을 가져옵니다.

### 반환

A [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)은(는) 
             슬라이드 좌표계에서 도형의 시각적 경계 영역을 나타냅니다.



```python
def get_visual_bounds(self):
    ...
```


### 비고

반환된 사각형은 슬라이드 좌표 공간에서 렌더링 중 도형에 의해 생성된 모든 콘텐츠의 축에 정렬된 경계 영역을 나타냅니다.
            
            이 경계는 도형의 모델 경계([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))와 다를 수 있으며, 렌더링된 콘텐츠가 슬라이드 원점을 초과하면 음수 좌표를 포함할 수 있습니다.
            
            시각적 경계는 변환(예: 회전), 선 두께 및 이음, 텍스트 레이아웃 및 넘침, SmartArt 기하학 및 도형의 최종 렌더링 모습에 영향을 주는 기타 레이아웃 효과 등 렌더링 관련 요소를 고려합니다.
            
            반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.



### 참고
* 클래스 [`AudioFrame`](/slides/python-net/ko/aspose.slides/audioframe)
* 클래스 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)