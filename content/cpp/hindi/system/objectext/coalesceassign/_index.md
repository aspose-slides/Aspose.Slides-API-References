---
title: CoalesceAssign()
second_title: Aspose.Slides C++ के लिए एपीआई संदर्भ
description: ‘??=’ ऑपरेटर अनुवाद का कार्यान्वयन।
type: docs
weight: 183
url: /hi/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) विधि

'??=' ऑपरेटर अनुवाद का कार्यान्वयन।

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T0 | LHS मान प्रकार। |
| T1 | RHS अभिव्यक्ति को सम्मिलित करने वाले लैम्ब्डा का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T0\& | LHS मान। |
| func | T1 | RHS अभिव्यक्ति। |

### वापसी मान

यदि LHS मान null नहीं है तो LHS लौटाता है, अन्यथा RHS अभिव्यक्ति की गणना करता है और परिणाम लौटाता है।

## देखें

* क्लास [ObjectExt](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)