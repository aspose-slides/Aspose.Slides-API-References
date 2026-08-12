---
title: CoalesceInternal()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: नॉन-नल प्रकारों के लिए '??' ऑपरेटर का कार्यान्वयन। यदि RT2 को RT1 में परिवर्तित किया जा सकता है तो ओवरलोड।
type: docs
weight: 157
url: /hi/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) मेथड

'??' ऑपरेटर का अनुवाद गैर-नल प्रकारों के लिए लागू किया गया है। यदि RT2 को RT1 में परिवर्तित किया जा सकता है, तो ओवरलोड।

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### टेम्पलेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| value | RT1 | LHS value. |
| func | F | RHS expression. |

### रिटर्न वैल्यू

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## देखें भी

* क्लास [ObjectExt](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)