---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠를 기반으로 계산된 도형의 시각적 경계를 가져옵니다.

### 반환값

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.

```python
def get_visual_bounds(self):
    ...
```

### 비고

반환된 사각형은 슬라이드 좌표 공간에서 렌더링 중 도형에 의해 생성된 모든 콘텐츠의 축에 정렬된 경계를 나타냅니다.
             이 경계는 도형의 모델 경계([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))와 다를 수 있으며, 렌더링된 콘텐츠가 슬라이드 원점을 넘어 확장될 경우 음수 좌표를 포함할 수 있습니다.
             시각적 경계는 변환(예: 회전), 스트로크 두께 및 연결, 텍스트 레이아웃 및 오버플로, SmartArt 기하학 및 도형의 최종 렌더링된 모습에 영향을 주는 기타 레이아웃 효과와 같은 렌더링 관련 요소를 고려합니다.
             반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.

### 관련 항목
* 클래스 [`PictureFrame`](/slides/python-net/ko/aspose.slides/pictureframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)