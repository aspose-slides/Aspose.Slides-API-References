---
title: operator!=()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित करता है कि वर्तमान और निर्दिष्ट TypeInfo ऑब्जेक्ट समान नहीं हैं।
type: docs
weight: 456
url: /hi/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const मेथड

निर्धारित करता है कि वर्तमान और निर्दिष्ट [TypeInfo](../) ऑब्जेक्ट समान नहीं हैं।

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | तुलना करने हेतु [TypeInfo](../) ऑब्जेक्ट |

### वापसी मान

सही यदि ऑब्जेक्ट के हैश समान नहीं हैं, अन्यथा - गलत

## TypeInfo::operator!=(std::nullptr_t) const मेथड

निर्धारित करता है कि वर्तमान [TypeInfo](../) ऑब्जेक्ट शून्य-ऑब्जेक्ट नहीं है, अर्थात यह किसी प्रकार को दर्शाता है।

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### वापसी मान

सही यदि वर्तमान [TypeInfo](../) ऑब्जेक्ट शून्य-ऑब्जेक्ट नहीं है, अन्यथा - गलत

## देखें

* क्लास [TypeInfo](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)