---
title: Equals< float, float >()
second_title: Aspose.Slides C++ API संदर्भ
description: "एकल-प्रेसिशन फ्लोटिंग पॉइंट मानों के लिए विशेषीकरण। हालांकि दो फ्लोटिंग पॉइंट NaN को IEC 60559:1989 द्वारा हमेशा असमान मानते हुए परिभाषित किया गया है, System.Object.Equals के अनुबंध के अनुसार, ओवरराइड्स को समानता ऑपरेटर की आवश्यकताओं को पूरा करना आवश्यक है। इसलिए, System.Double.Equals और System.Single.Equals दो NaN की तुलना करते समय True लौटाते हैं, जबकि समानता ऑपरेटर इस स्थिति में False लौटाता है, जैसा कि मानक द्वारा आवश्यक है।"
type: docs
weight: 2705
url: /hi/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float&, const float&) फ़ंक्शन

एकल-प्रेसिशन फ्लोटिंग पॉइंट मूल्यों के लिए विशेषीकरण। हालांकि दो फ्लोटिंग पॉइंट NaN को IEC 60559:1989 द्वारा हमेशा असमान मानने के लिये परिभाषित किया गया है, [System.Object.Equals](../object/equals/) के लिए अनुबंध यह निर्धारित करता है कि ओवरराइड्स को समानता ऑपरेटर की आवश्यकताओं को पूरा करना चाहिए। इसलिए, System.Double.Equals और System.Single.Equals दो NaN की तुलना करते समय True लौटाते हैं, जबकि समानता ऑपरेटर इस स्थिति में False लौटाता है, जैसा कि मानक द्वारा आवश्यक है।

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const **float**\& | पहला तुलनात्मक मान |
| b | const **float**\& | दूसरा तुलनात्मक मान |

### रिटर्न वैल्यू

यदि दोनों मान NaN हैं या बराबर हैं तो True, अन्यथा - false

## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)