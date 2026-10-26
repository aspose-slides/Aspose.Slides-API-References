---
title: operator==()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि वर्तमान और निर्दिष्ट TypeInfo वस्तुएँ समान हैं।
type: docs
weight: 443
url: /hi/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const विधि


निर्धारित करता है कि वर्तमान और निर्दिष्ट [TypeInfo](../) वस्तुएँ समान हैं।

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | तुलना करने के लिए [TypeInfo](../) वस्तु |

### वापसी मान

सही यदि वस्तुओं के हैश समान हों, अन्यथा - गलत

## TypeInfo::operator==(std::nullptr_t) const विधि


निर्धारित करता है कि वर्तमान [TypeInfo](../) वस्तु एक null-object है, अर्थात् कोई प्रकार दर्शाता नहीं है।

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```


### वापसी मान

सही यदि वर्तमान [TypeInfo](../) वस्तु एक null-object है, अन्यथा - गलत

## देखें भी

* क्लास [TypeInfo](../)
* नामस्थान [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)