---
title: Add()
second_title: Aspose.Slides için C++ API Referansı
description: Yola yeni komut ekle
type: docs
weight: 14
url: /tr/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method

Yola yeni komut ekle

```cpp
virtual System::SharedPtr<IMotionCmd> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Animasyon hareket etkisi davranışı için komutun tipi [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Noktalar dizisi [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Animasyon hareket yolundaki noktaların tipi [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Göreceli koordinatların kullanılıp kullanılmayacağını belirtir **bool** |

### Return Value

Yolun komutu [IMotionCmdPath](../../imotioncmdpath/)

## İlgili

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IMotionCmdPath](../../imotioncmdpath/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)