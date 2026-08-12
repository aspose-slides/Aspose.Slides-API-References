---
title: AreEqualContainer()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऑपरेटर == का उपयोग करके तत्वों पर दो कंटेनरों की समानता की तुलना करता है। यह non-SmartPtr तत्वों के लिए काम करता है।
type: docs
weight: 1
url: /hi/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) फ़ंक्शन

ऑपरेटर == का उपयोग करके दो कंटेनरों की समानता की तुलना करता है। यह non-SmartPtr तत्वों के लिए काम करता है।

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS कंटेनर प्रकार। |
| T2 | RHS कंटेनर प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | const T1\& | LHS कंटेनर। |
| rhs | const T2\& | RHS कंटेनर। |

### वापसी मान

यदि शामिल तत्व और आकार मेल खाते हैं तो true, अन्यथा false।

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) फ़ंक्शन

ऑपरेटर [System::Object::Equals](../../system/object/equals/) का उपयोग करके दो कंटेनरों की समानता की तुलना करता है। यह [SmartPtr](../../system/smartptr/) तत्वों के लिए काम करता है।

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS कंटेनर प्रकार। |
| T2 | RHS कंटेनर प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | const T1\& | LHS कंटेनर रेफ़रेंस। |
| rhs | const T2\& | RHS कंटेनर रेफ़रेंस। |

### वापसी मान

यदि शामिल तत्व और आकार मेल खाते हैं तो true, अन्यथा false।

## संबंधित देखें

* संरचना [IsSmartPtr](../../system/issmartptr/)
* नेमस्पेस [System::TestPredicates::Details::SharedPtrAsserts](../)
* लाइब्रेरी [Aspose.Slides](../../)