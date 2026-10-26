---
title: Add()
second_title: Aspose.Slides για C++ API Reference
description: Προσθήκη νέας εντολής στη διαδρομή
type: docs
weight: 14
url: /el/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) μέθοδος

Προσθέστε νέα εντολή στη διαδρομή

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Τύπος εντολής για τη συμπεριφορά του εφέ κίνησης της ανιμέσας [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Διάταξη σημείων [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Τύπος σημείων στη διαδρομή κίνησης της ανιμέσας [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Καθορίζει εάν θα χρησιμοποιηθούν σχετικές συντεταγμένες ή όχι **bool** |

### Τιμή Επιστροφής

Εντολή διαδρομής [IMotionCmdPath](../../imotioncmdpath/)

## Δείτε επίσης

* Απαρίθμηση [MotionCommandPathType](../../motioncommandpathtype/)
* Απαρίθμηση [MotionPathPointsType](../../motionpathpointstype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IMotionCmdPath](../../imotioncmdpath/)
* Κλάση [PointF](../../../system.drawing/pointf/)
* Κλάση [IMotionPath](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)