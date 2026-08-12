---
title: NullableBoolHelper()
second_title: Aspose.Slides for C++ API संदर्भ
description: सहायक फ़ंक्शन जो जाँचता है कि यह और अन्य दोनों null नहीं हैं और यदि ऐसा है तो एक लैम्ब्डा को कॉल करता है। implementation.s में उपयोग किया गया।
type: docs
weight: 105
url: /hi/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const मेथड

इस और **other** दोनों को null न होने की जाँच करने और यदि ऐसा हो तो एक लैम्बडा को कॉल करने के लिए सहायक फ़ंक्शन। implementation.s में उपयोग किया जाता है।

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | अन्य nullable प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| other | const T1\& | तुलना करने के लिए अन्य nullable मान। |
| f | const std::function\<**bool**()>\& | यदि दोनों **this** और **other** null नहीं हैं तो कॉल करने के लिए लैम्बडा। |
| default_if_both_are_null | **bool** | यदि दोनों मान null हैं तो लौटाने वाला मान। |

### रिटर्न वैल्यू

यदि **this** या **other** में से कोई भी null है तो false; यदि दोनों null हैं तो **default_if_both_are_null**; यदि दोनों null नहीं हैं तो **f** कॉल का परिणाम।

## देखें

* क्लास [Nullable](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)