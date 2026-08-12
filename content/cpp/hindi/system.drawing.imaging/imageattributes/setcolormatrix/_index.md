---
title: SetColorMatrix()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: रंग-समायोजन मैट्रिक्स सेट करता है।
type: docs
weight: 183
url: /hi/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) विधि


रंग-समायोजन मैट्रिक्स सेट करता है।

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | सेट करने के लिए रंग-समायोजन मैट्रिक्स |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | रंग-समायोजन मैट्रिक्स द्वारा प्रभावित होने वाली छवि और रंग के प्रकार को निर्दिष्ट करता है |
| type | [ColorAdjustType](../../coloradjusttype/) | जिस वस्तुओं के लिए रंग-समायोजन मैट्रिक्स सेट किया जाता है, उनके प्रकार को निर्धारित करता है |

## संबंधित देखें

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ColorMatrix](../../colormatrix/)
* क्लास [ImageAttributes](../)
* नेमस्पेस [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)