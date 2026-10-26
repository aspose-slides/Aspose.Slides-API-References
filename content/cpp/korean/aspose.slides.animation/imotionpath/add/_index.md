---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경로에 새 명령을 추가합니다
type: docs
weight: 14
url: /ko/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


경로에 새 명령을 추가합니다

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | 애니메이션 모션 효과 동작을 위한 명령 유형 [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | 점 배열 [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | 애니메이션 모션 경로의 점 유형 [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | 상대 좌표를 사용할지 여부를 표시합니다 **bool** |

### 반환값

경로의 명령 [IMotionCmdPath](../../imotioncmdpath/)

## 관련 항목

* 열거형 [MotionCommandPathType](../../motioncommandpathtype/)
* 열거형 [MotionPathPointsType](../../motionpathpointstype/)
* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IMotionCmdPath](../../imotioncmdpath/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [IMotionPath](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)