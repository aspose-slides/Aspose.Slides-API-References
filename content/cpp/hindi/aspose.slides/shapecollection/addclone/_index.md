---
title: AddClone()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट आकार की एक प्रति बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 547
url: /hi/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) विधि

निर्दिष्ट आकार की एक प्रति बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए आकार। |
| x | **float** | नए आकार के फ्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | नए आकार के फ्रेम का y-निर्देशांक, बिंदुओं में। |
| width | **float** | नए आकार के फ्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | नए आकार के फ्रेम की ऊँचाई, बिंदुओं में। |

### वापसी मान

नया बनाया गया [IShape](../../ishape/)।

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) विधि

निर्दिष्ट आकार की एक प्रति बनाता है और उसे आकार संग्रह के अंत में जोड़ता है। नया आकार *sourceShape* की चौड़ाई और ऊँचाई को बनाए रखता है।

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए आकार। |
| x | **float** | नए आकार के फ्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | नए आकार के फ्रेम का y-निर्देशांक, बिंदुओं में। |

### वापसी मान

नया बनाया गया [IShape](../../ishape/)।

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) विधि

निर्दिष्ट आकार की एक प्रति बनाता है और उसे आकार संग्रह के अंत में जोड़ता है। क्लोन किया गया आकार मूल आकार की स्थिति और आकार को बनाए रखता है।

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | क्लोन करने के लिए [IShape](../../ishape/)। |

### वापसी मान

नया बनाया गया [IShape](../../ishape/)।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* वर्ग [IShape](../../ishape/)
* वर्ग [ShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)