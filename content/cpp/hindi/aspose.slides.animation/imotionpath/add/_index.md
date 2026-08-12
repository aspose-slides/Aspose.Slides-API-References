---
title: Add()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: पथ में नया कमांड जोड़ें
type: docs
weight: 14
url: /hi/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


पथ में नया कमांड जोड़ें

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | एनिमेशन गति प्रभाव व्यवहार के लिए कमांड का प्रकार [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | पॉइंट्स एरे [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | एनिमेशन गति पथ में बिंदुओं का प्रकार [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | सापेक्ष निर्देशांक का उपयोग करना है या नहीं, दर्शाता है **bool** |

### रिटर्न वैल्यू

पथ का कमांड [IMotionCmdPath](../../imotioncmdpath/)

## संबंधित देखें

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IMotionCmdPath](../../imotioncmdpath/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [IMotionPath](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)