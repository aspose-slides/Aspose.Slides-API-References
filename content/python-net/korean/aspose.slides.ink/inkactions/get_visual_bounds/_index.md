---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
렌더링된 내용으로부터 계산된 도형의 시각적 경계를 가져옵니다.

### 반환
A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### 비고
 The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
             
             This bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
             
             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
             
             The returned bounds are not clipped to the slide rectangle.



### 참조
* 클래스 [`InkActions`](/slides/python-net/ko/aspose.slides.ink/inkactions)
* 모듈 [`aspose.slides.ink`](/slides/python-net/ko/aspose.slides.ink)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)