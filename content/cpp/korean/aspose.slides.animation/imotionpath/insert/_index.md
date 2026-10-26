---
title: Insert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경로에 새 명령을 삽입합니다
type: docs
weight: 27
url: /ko/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) 메서드

경로에 새 명령을 삽입합니다

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 명령 삽입을 위한 인덱스 **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | 애니메이션 모션 효과 동작을 위한 명령 유형 [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | 포인트 배열 [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | 애니메이션 모션 경로의 포인트 유형 [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | 상대 좌표를 사용할지 여부를 나타냅니다 **bool** |

## 참조

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)