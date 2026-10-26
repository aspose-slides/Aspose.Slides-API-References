---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
렌더링된 내용으로부터 계산된 도형의 시각적 경계를 가져옵니다.

### 반환
[`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)는 슬라이드 좌표계에서 도형의 시각적 경계를 나타냅니다.

```python
def get_visual_bounds(self):
    ...
```

### 비고
반환된 사각형은 모든 콘텐츠의 축에 정렬된 경계를 나타냅니다
             도형이 슬라이드 좌표계에서 렌더링되는 동안 생성된 콘텐츠

             이러한 경계는 도형의 모델 경계와 다를 수 있습니다
             ([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))
             슬라이드 원점을 넘어 확장되는 경우 음수 좌표를 포함할 수 있습니다

             시각적 경계는 렌더링 관련 요소를 고려합니다(예를 들어
             변환(예: 회전), 선 두께 및 조인,
             텍스트 레이아웃 및 오버플로, SmartArt 기하학, 및 기타 레이아웃 효과
             도형의 최종 렌더링된 외관에 영향을 줍니다

             반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.

### 또한 보기
* 클래스 [`VideoFrame`](/slides/python-net/ko/aspose.slides/videoframe)
* 클래스 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)