---
title: get_visual_bounds method
second_title: Aspose.Slides Python용 .NET API 레퍼런스
description:
type: docs
url: /ko/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠를 기반으로 계산된 형상의 시각적 경계값을 가져옵니다.

### 반환

A **aspose.slides.RectangleF**는 형상의 시각적 경계를 슬라이드 좌표계에서 나타냅니다.



```python
def get_visual_bounds(self):
    ...
```


### 비고

The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
             The returned bounds are not clipped to the slide rectangle.



### 관련 항목
* 클래스 [`VideoFrame`](/slides/python-net/ko/aspose.slides/videoframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)