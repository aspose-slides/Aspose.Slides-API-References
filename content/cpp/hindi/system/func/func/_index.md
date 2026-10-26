---
title: Func()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डिफ़ॉल्ट कन्स्ट्रक्टर जो null-Func बनाता है।
type: docs
weight: 1
url: /hi/system/func/func/
---
## Func::Func() कन्स्ट्रक्टर

डिफ़ॉल्ट कन्स्ट्रक्टर जो null-Func बनाता है।

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) कन्स्ट्रक्टर

[Func](../) ऑब्जेक्ट को बनाता है और इसे मान (वास्तविक कॉलबैक या nullptr) असाइन करता है।

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तर्क प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg | T\&& | तर्क। |

## Func::Func(const Func\&) कन्स्ट्रक्टर

कॉपी कन्स्ट्रक्टर।

```cpp
System::Func<Args>::Func(const Func &func)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) से डेटा कॉपी करने के लिए। |

## Func::Func(Func\&&) कन्स्ट्रक्टर

मूव कन्स्ट्रक्टर।

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) से डेटा मूव करने के लिए। |

## संबंधित देखें

* क्लास [Func](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)