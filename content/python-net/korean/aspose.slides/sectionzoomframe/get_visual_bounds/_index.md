---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠에서 계산된 도형의 시각적 경계를 가져옵니다.

### Returns

도형의 시각적 경계를 나타내는 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
             슬라이드 좌표계에서.

```python
def get_visual_bounds(self):
    ...
```

### Remarks

반환된 사각형은 모든 콘텐츠의 축에 정렬된 경계를 나타냅니다
             슬라이드 좌표 공간에서 렌더링되는 동안 도형에 의해 생성된

이러한 경계는 도형의 모델 경계와 다를 수 있습니다
             ([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))
             그리고 렌더링된 콘텐츠가 확장될 경우 음수 좌표를 포함할 수 있습니다
             슬라이드 원점을 넘어

시각적 경계는 다음과 같은 렌더링 관련 요소를 고려합니다
             변환(예: 회전), 스트로크 너비와 조인,
             텍스트 레이아웃 및 오버플로우, SmartArt 기하학, 및 기타 레이아웃 효과
             도형의 최종 렌더링된 모습에 영향을 줍니다

반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.

### See Also
* class [`SectionZoomFrame`](/slides/python-net/ko/aspose.slides/sectionzoomframe)
* class [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)