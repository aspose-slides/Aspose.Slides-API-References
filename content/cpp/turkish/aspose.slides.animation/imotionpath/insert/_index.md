---
title: Insert()
second_title: Aspose.Slides for C++ API Referansı
description: Yola yeni komut ekle
type: docs
weight: 27
url: /tr/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metod

Yeni komutu yola ekle

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Komut ekleme için indeks **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Animasyon hareket efekti davranışı için komut tipi [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Nokta dizisi [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Animasyon hareket yolundaki noktaların türü [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Göreceli koordinatların kullanılıp kullanılmayacağını belirtir **bool** |

## Ayrıca

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [IMotionPath](../)
* AdAlanı [Aspose::Slides::Animation](../../)
* Kütüphane [Aspose.Slides](../../../)