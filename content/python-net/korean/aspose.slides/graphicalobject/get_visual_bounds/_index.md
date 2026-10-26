---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠에서 계산된 도형의 시각적 경계를 가져옵니다.

### Returns

슬라이드 좌표계에서 도형의 시각적 경계를 나타내는 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)입니다.
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

반환된 사각형은 모든 콘텐츠의 축 정렬 경계를 나타냅니다
             produced by the shape during rendering in slide coordinate space.
            
             이 경계는 도형의 모델 경계와 다를 수 있습니다
             ([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             시각적 경계는 다음과 같은 렌더링 관련 요소를 고려합니다
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
             반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.



### See Also
* 클래스 [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* 클래스 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)