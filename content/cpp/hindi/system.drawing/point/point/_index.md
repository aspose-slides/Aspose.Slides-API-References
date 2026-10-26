---
title: Point()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया Point ऑब्जेक्ट बनाता है और उसके X और Y निर्देशांक मानों को 0 से प्रारम्भ करता है।
type: docs
weight: 1
url: /hi/system.drawing/point/point/
---
## Point::Point() कंस्ट्रक्टर

एक नया [Point](../) वस्तु बनाता है और उसके X और Y निर्देशांक मानों को 0 से प्रारम्भ करता है।

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) कंस्ट्रक्टर

एक नया [Point](../) वस्तु बनाता है और इसे निर्दिष्ट मानों से प्रारम्भ करता है।

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | X निर्देशांक का मान |
| y | int | Y निर्देशांक का मान |

## Point::Point(const Size\&) कंस्ट्रक्टर

एक नया [Point](../) वस्तु बनाता है और उसके X और Y निर्देशांक मानों को निर्दिष्ट [SizeF](../../sizef/) वस्तु की चौड़ाई और ऊँचाई के मानों से क्रमशः प्रारम्भ करता है।

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| size | const [Size](../../size/)\& | एक [SizeF](../../sizef/) वस्तु जिसकी चौड़ाई और ऊँचाई मानों का उपयोग निर्मित हो रहे [Point](../) वस्तु के X और Y निर्देशांक मानों को प्रारम्भ करने में किया जाता है |

## Point::Point(int) कंस्ट्रक्टर

एक नया [Point](../) वस्तु बनाता है और उसके X निर्देशांक मान को निर्दिष्ट 32-बिट पूर्णांक के उच्च 16 बिट्स द्वारा निर्मित मान से तथा उसके Y निर्देशांक मान को निर्दिष्ट 32-बिट पूर्णांक के निम्न 16 बिट्स द्वारा निर्मित मान से प्रारम्भ करता है।

```cpp
System::Drawing::Point::Point(int dw)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dw | int | वह 32-बिट पूर्णांक मान जिसके उच्च 16 बिट्स X निर्देशांक मान और निम्न 16 बिट्स Y निर्देशांक मान को निर्दिष्ट करते हैं |

## देखें

* क्लास [Point](../)
* क्लास [Size](../../size/)
* नामस्थान [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)