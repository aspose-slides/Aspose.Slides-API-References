---
title: TestTools
second_title: Aspose.Slides for C++ API संदर्भ
description: विभिन्न प्रकारों और फ़ंक्शनों की कुछ मूलभूत विशेषताओं की जाँच करने वाली उपयोगी विधियों का एक सेट प्रदान करता है।
type: docs
weight: 1925
url: /hi/system/testtools/
---
## TestTools struct

विभिन्न प्रकारों और फ़ंक्शनों की कुछ मूलभूत विशेषताओं की जाँच करने वाले उपयोगी विधियों का एक सेट प्रदान करता है।

```cpp
class TestTools
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | जाँचता है कि फ़ंक्शन किसी भी प्रकार का अपवाद फेंकता है या नहीं। |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | जाँचता है कि स्ट्रिंग खाली है या नहीं। |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | जाँचता है कि संग्रह खाली है या नहीं। |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | जाँचता है कि विशिष्ट मान null है। [Version](../version/) अंकात्मक और enum प्रकारों के लिए। |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | जाँचता है कि विशिष्ट मान null है। [Version](../version/) गैर-अंकात्मक और गैर-enum मान प्रकारों के लिए। |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | जाँचता है कि विशिष्ट मान null है। [Version](../version/) गैर-अंकात्मक मान प्रकारों के लिए। |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | जाँचता है कि विशिष्ट मान null है। [Version](../version/) कुंजी-मूल्य युग्मों के लिए। |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | जाँचता है कि स्ट्रिंग null है या नहीं। |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | जाँचता है कि संग्रह null है या खाली है। |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | जाँचता है कि स्ट्रिंग null है या खाली है। |
## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)