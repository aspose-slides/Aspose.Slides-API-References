---
title: add method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.animation/imotionpath/add/
weight: 10
---
## add(self, type, pts, pts_type, b_relative_coord) {#motioncommandpathtype-listasposeslidespointf-motionpathpointstype-bool}
경로에 새 명령을 추가합니다

### 반환값

경로의 명령 [`IMotionCmdPath`](/slides/python-net/ko/aspose.slides.animation/imotioncmdpath)



```python
def add(self, type, pts, pts_type, b_relative_coord):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| type | [`MotionCommandPathType`](/slides/python-net/ko/aspose.slides.animation/motioncommandpathtype) | 애니메이션 모션 효과 동작에 대한 명령 유형 [`MotionCommandPathType`](/slides/python-net/ko/aspose.slides.animation/motioncommandpathtype) |
| pts | **List[aspose.slides.PointF]** | 포인트 배열 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)[] |
| pts_type | [`MotionPathPointsType`](/slides/python-net/ko/aspose.slides.animation/motionpathpointstype) | 애니메이션 모션 경로의 포인트 유형 [`MotionPathPointsType`](/slides/python-net/ko/aspose.slides.animation/motionpathpointstype) |
| b_relative_coord | **bool** | 상대 좌표를 사용할지 여부를 나타냅니다 **bool** |



### 참고
* 클래스 [`IMotionCmdPath`](/slides/python-net/ko/aspose.slides.animation/imotioncmdpath)
* 클래스 [`IMotionPath`](/slides/python-net/ko/aspose.slides.animation/imotionpath)
* 열거형 [`MotionCommandPathType`](/slides/python-net/ko/aspose.slides.animation/motioncommandpathtype)
* 열거형 [`MotionPathPointsType`](/slides/python-net/ko/aspose.slides.animation/motionpathpointstype)
* 클래스 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)