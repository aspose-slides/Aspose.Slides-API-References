---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan perintah baru ke jalur
type: docs
weight: 14
url: /id/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method

Menambahkan perintah baru ke jalur

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Type of command for animation motion effect behavior [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Points array [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Type of points in animation motion path [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indicates whether to use relative coordinates or not **bool** |

### Nilai Kembali

Command of a path [IMotionCmdPath](../../imotioncmdpath/)

## Lihat Juga

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IMotionCmdPath](../../imotioncmdpath/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Kelas [IMotionPath](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)