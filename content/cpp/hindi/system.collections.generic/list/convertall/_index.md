---
title: ConvertAll()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: विभिन्न प्रकार में परिवर्तित तत्वों की एक सूची बनाता है।
type: docs
weight: 352
url: /hi/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) विधि

विभिन्न प्रकार में परिवर्तित तत्वों की एक सूची बनाता है।

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| OutputType | आउटपुट सूची तत्व का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | आइटम्स के रूपांतरण के लिए उपयोग किया जाने वाला कनवर्टर। |

### वापसी मान

परिवर्तित तत्वों की नई बनाई गई सूची।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)