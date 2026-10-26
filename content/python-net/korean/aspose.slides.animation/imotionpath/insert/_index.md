---
title: insert method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.animation/imotionpath/insert/
weight: 30
---
## insert(self, index, type, pts, pts_type, b_relative_coord) {#int-motioncommandpathtype-listasposeslidespointf-motionpathpointstype-bool}
경로에 새 명령을 삽입합니다


```python
def insert(self, index, type, pts, pts_type, b_relative_coord):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 명령 삽입을 위한 인덱스 **int** |
| type | [`MotionCommandPathType`](/slides/python-net/ko/aspose.slides.animation/motioncommandpathtype) | 애니메이션 모션 효과 동작에 대한 명령 유형 [`MotionCommandPathType`](/slides/python-net/ko/aspose.slides.animation/motioncommandpathtype) |
| pts | **List[aspose.slides.PointF]** | 점 배열 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)[] |
| pts_type | [`MotionPathPointsType`](/slides/python-net/ko/aspose.slides.animation/motionpathpointstype) | 애니메이션 모션 경로의 점 유형 [`MotionPathPointsType`](/slides/python-net/ko/aspose.slides.animation/motionpathpointstype) |
| b_relative_coord | **bool** | 상대 좌표를 사용할지 여부를 나타냅니다 **bool** |



### 관련 항목
* 클래스 [`IMotionPath`](/slides/python-net/ko/aspose.slides.animation/imotionpath)
* 열거형 [`MotionCommandPathType`](/slides/python-net/ko/aspose.slides.animation/motioncommandpathtype)
* 열거형 [`MotionPathPointsType`](/slides/python-net/ko/aspose.slides.animation/motionpathpointstype)
* 클래스 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)