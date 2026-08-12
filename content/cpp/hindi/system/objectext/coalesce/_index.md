---
title: Coalesce()
second_title: Aspose.Slides for C++ API संदर्भ
description: "'??' ऑपरेटर अनुवाद का कार्यान्वयन नॉन-नुलेबल प्रकारों के लिए।"
type: docs
weight: 170
url: /hi/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) मेथड

'??' ऑपरेटर अनुवाद का कार्यान्वयन नॉन-नुलेबल प्रकारों के लिए।

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T0 | LHS मान प्रकार। |
| T1 | RHS अभिव्यक्ति को सम्मिलित करने वाले लैम्ब्डा का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | T0 | LHS मान। |
| func | T1 | RHS अभिव्यक्ति। |

### रिटर्न वैल्यू

यदि LHS मान null नहीं है, तो LHS लौटाता है, अन्यथा RHS अभिव्यक्ति की गणना करता है और परिणाम लौटाता है।

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) मेथड

'??' ऑपरेटर अनुवाद का कार्यान्वयन नल एबल प्रकारों के लिए।

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T0 | LHS मान प्रकार। |
| T1 | RHS अभिव्यक्ति को सम्मिलित करने वाले लैम्ब्डा का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS मान। |
| func | T1 | RHS अभिव्यक्ति। |

### रिटर्न वैल्यू

यदि LHS मान null नहीं है, तो LHS लौटाता है, अन्यथा RHS अभिव्यक्ति की गणना करता है और परिणाम लौटाता है।

## देखें

* क्लास [ObjectExt](../)
* क्लास [Nullable](../../nullable/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)