---
title: Insert()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Wstaw nową komendę do ścieżki
type: docs
weight: 27
url: /pl/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metoda

Wstaw nową komendę do ścieżki

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks do wstawiania komendy **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Typ komendy dla zachowania efektu ruchu animacji [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Tablica punktów [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Typ punktów w ścieżce ruchu animacji [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Określa, czy używać współrzędnych względnych, czy nie **bool** |

## Zobacz także

* Wyliczenie [MotionCommandPathType](../../motioncommandpathtype/)
* Wyliczenie [MotionPathPointsType](../../motionpathpointstype/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [PointF](../../../system.drawing/pointf/)
* Klasa [IMotionPath](../)
* Przestrzeń nazw [Aspose::Slides::Animation](../../)
* Biblioteka [Aspose.Slides](../../../)