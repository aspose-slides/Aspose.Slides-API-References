---
title: AreEqualData()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "तत्वों पर System::Object::Equals का उपयोग करके दो कंटेनरों की समानता की तुलना करता है। SmartPtr तत्वों के लिए कार्य करता है।"
type: docs
weight: 14
url: /hi/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) फ़ंक्शन

तत्वों पर [System::Object::Equals](../../system/object/equals/) का उपयोग करके दो कंटेनरों की समानता की तुलना करता है। [SmartPtr](../../system/smartptr/) तत्वों के लिए कार्य करता है।

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS कंटेनर प्रकार। |
| T2 | RHS कंटेनर प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | const T1\& | LHS कंटेनर रेफ़रेंस। |
| rhs | const T2\& | RHS कंटेनर रेफ़रेंस। |

### रिटर्न मान

यदि समाहित तत्व और आकार मेल खाते हैं तो true, अन्यथा false।

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) फ़ंक्शन

तत्वों पर operator == का उपयोग करके दो कंटेनरों की समानता की तुलना करता है। non-SmartPtr तत्वों के लिए कार्य करता है।

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS कंटेनर प्रकार। |
| T2 | RHS कंटेनर प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | const T1\& | LHS कंटेनर। |
| rhs | const T2\& | RHS कंटेनर। |

### रिटर्न मान

यदि समाहित तत्व और आकार मेल खाते हैं तो true, अन्यथा false।

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) फ़ंक्शन

एक ही प्रकार के दो कंटेनरों की समानता की तुलना करता है। non-SmartPtr तत्वों के लिए कार्य करता है।

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T1 | LHS कंटेनर प्रकार। |
| T2 | RHS कंटेनर प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | const T\& | LHS कंटेनर। |
| rhs | const T\& | RHS कंटेनर। |

### रिटर्न मान

यदि समाहित तत्व और आकार मेल खाते हैं तो true, अन्यथा false।

## संबंधित देखें

* स्ट्रक्ट [IsSmartPtr](../../system/issmartptr/)
* नेमस्पेस [System::TestPredicates::Details::SharedPtrAsserts](../)
* लाइब्रेरी [Aspose.Slides](../../)