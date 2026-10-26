---
title: AddControl()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: संग्रह में नया नियंत्रण बनाता है और जोड़ता है।
type: docs
weight: 53
url: /hi/aspose.slides/icontrolcollection/addcontrol/
---
## IControlCollection::AddControl(ControlType, float, float, float, float) विधि

नया नियंत्रण बनाता है और संग्रह में जोड़ता है।

```cpp
virtual System::SharedPtr<IControl> Aspose::Slides::IControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | जोड़ने के लिए नियंत्रण का प्रकार। |
| x | **float** | आकार के फ्रेम के बाएँ पक्ष के लिए X-निर्देशांक। |
| y | **float** | आकार के फ्रेम के शीर्ष पक्ष के लिए Y-निर्देशांक। |
| width | **float** | आकार के फ्रेम की चौड़ाई। |
| height | **float** | आकार के फ्रेम की ऊँचाई। |

### Return Value

निर्मित नियंत्रण [IControl](../../icontrol/)।

## See Also

* Enum [ControlType](../../controltype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IControl](../../icontrol/)
* Class [IControlCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)