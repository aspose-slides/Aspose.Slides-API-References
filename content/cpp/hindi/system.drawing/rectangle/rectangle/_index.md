---
title: Rectangle()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया Rectangle ऑब्जेक्ट बनाता है जो X और Y निर्देशांक, तथा चौड़ाई और ऊँचाई मान 0 पर सेट की गई आयत का प्रतिनिधित्व करता है।
type: docs
weight: 1
url: /hi/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() कन्स्ट्रक्टर

एक नया [Rectangle](../) ऑब्जेक्ट बनाता है जो X और Y निर्देशांक तथा चौड़ाई और ऊँचाई मान 0 पर सेट करता है।

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) कन्स्ट्रक्टर

एक नया [Rectangle](../) ऑब्जेक्ट बनाता है जो आयत का प्रतिनिधित्व करता है, जिसके ऊपरी बाएँ कोने के निर्दिष्ट निर्देशांक और चौड़ाई तथा ऊँचाई होते हैं।

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | आयत के ऊपरी बाएँ कोने का X निर्देशांक |
| y | int | आयत के ऊपरी बाएँ कोने का Y निर्देशांक |
| width | int | आयत की चौड़ाई |
| height | int | आयत की ऊँचाई |

## Rectangle::Rectangle(const Point\&, const Size\&) कन्स्ट्रक्टर

एक नया [Rectangle](../) ऑब्जेक्ट बनाता है जो आयत का प्रतिनिधित्व करता है, जिसके ऊपरी बाएँ कोने के निर्देशांक को [Point](../../point/) क्लास के एक इंस्टेंस के रूप में और उसकी चौड़ाई व ऊँचाई को [Size](../../size/) क्लास के एक इंस्टेंस के रूप में निर्दिष्ट किया गया है।

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| location | const [Point](../../point/)\& | आयत के ऊपरी बाएँ कोने के स्थान को निर्दिष्ट करता है |
| size | const [Size](../../size/)\& | आयत की चौड़ाई और ऊँचाई को निर्दिष्ट करता है |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) कन्स्ट्रक्टर

एक नया [Rectangle](../) ऑब्जेक्ट बनाता है जो निर्दिष्ट आयत के बराबर आयत को दर्शाता है।

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | **System::Windows::Forms::Screen::Rectangle_** क्लास का एक इंस्टेंस जो बनाए जा रहे ऑब्जेक्ट द्वारा प्रतिनिधित्व किए जाने वाले आयत की स्थिति और आकार को निर्दिष्ट करता है |

## देखें

* क्लास [Rectangle](../)
* क्लास [Point](../../point/)
* क्लास [Size](../../size/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)