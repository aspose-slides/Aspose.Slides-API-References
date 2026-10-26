---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계를 가져옵니다.

### 반환

시각적 경계를 나타내는 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
             슬라이드 좌표계에서



```python
def get_visual_bounds(self):
    ...
```


### 비고

반환된 사각형은 모든 콘텐츠의 축 정렬 경계를 나타냅니다.
             도형에 의해 슬라이드 좌표계에서 렌더링되는 동안 생성된

             
             이 경계는 도형의 모델 경계와 다를 수 있습니다
             ([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))
             그리고 렌더링된 콘텐츠가 슬라이드 원점을 벗어나는 경우 음수 좌표를 포함할 수 있습니다
             
             시각적 경계는 다음과 같은 렌더링 관련 측면을 고려합니다
             변환(예: 회전), 획 두께 및 연결,
             텍스트 레이아웃 및 오버플로, SmartArt 기하학, 그리고 기타 레이아웃 효과
             이는 도형의 최종 렌더링된 외관에 영향을 미칩니다
             
             반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다



### 참고
* 클래스 [`GeometryShape`](/slides/python-net/ko/aspose.slides/geometryshape)
* 클래스 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)