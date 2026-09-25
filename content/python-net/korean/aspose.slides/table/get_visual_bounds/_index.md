---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
렌더링된 콘텐츠에서 계산된 도형의 시각적 경계를 가져옵니다.

### 반환값

[`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)는 도형의 시각적 경계를 나타내는
             슬라이드 좌표계에 해당합니다.



```python
def get_visual_bounds(self):
    ...
```


### 비고
반환된 사각형은 축에 정렬된 모든 콘텐츠의 경계를 나타냅니다
             도형이 슬라이드 좌표 공간에서 렌더링되는 동안 생성된.

이러한 경계는 도형의 모델 경계와 다를 수 있습니다
             ([`Shape.x`](/slides/python-net/ko/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ko/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ko/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ko/aspose.slides/shape/height))
             그리고 렌더링된 콘텐츠가 슬라이드 원점을 넘어 확장될 경우
             음수 좌표를 포함할 수 있습니다.

시각적 경계는 렌더링 관련 측면을 고려합니다
            변환(예: 회전), 획 두께와 조인,
            텍스트 레이아웃 및 오버플로, SmartArt 기하학, 그리고 기타 레이아웃 효과
            도형의 최종 렌더링된 모습에 영향을 줍니다.

반환된 경계는 슬라이드 사각형에 클리핑되지 않습니다.



### 참조
* 클래스 [`Table`](/slides/python-net/ko/aspose.slides/table)
* 클래스 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)