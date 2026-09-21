---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠를 기반으로 계산된 형상의 시각적 경계를 가져옵니다.

### Returns
슬라이드 좌표계에서 형상의 시각적 경계를 나타내는 **aspose.slides.RectangleF**.

```python
def get_visual_bounds(self):
    ...
```

### Remarks
반환된 사각형은 슬라이드 좌표 공간에서 렌더링 중 형상이 생성한 모든 콘텐츠의 축에 정렬된 경계를 나타냅니다.

이 경계는 형상의 모델 경계([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))와 다를 수 있으며, 렌더링된 콘텐츠가 슬라이드 원점을 벗어나는 경우 음수 좌표를 포함할 수 있습니다.

시각적 경계는 회전과 같은 변환, 스트로크 두께 및 조인, 텍스트 레이아웃 및 오버플로, SmartArt 기하학 및 형상의 최종 렌더링 외관에 영향을 미치는 기타 레이아웃 효과와 같은 렌더링 관련 요소를 고려합니다.

반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.

### See Also
* 클래스 [`AutoShape`](/slides/python-net/ko/aspose.slides/autoshape)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)