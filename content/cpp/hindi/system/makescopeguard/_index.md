---
title: MakeScopeGuard()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक फ़ैक्टरी फ़ंक्शन जो ScopedGuard क्लास की इंस्टेंस बनाता है।
type: docs
weight: 2809
url: /hi/system/makescopeguard/
---
## System::MakeScopeGuard(F) फ़ंक्शन

एक फ़ैक्टरी फ़ंक्शन जो ScopedGuard क्लास की इंस्टेंस बनाता है।

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| The | निर्मित ScopedGuard ऑब्जेक्ट द्वारा कॉल किए जाने वाले फ़ंक्शन ऑब्जेक्ट का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| f | F | ScopedGuard क्लास के कन्स्ट्रक्टर को पास किया जाने वाला फ़ंक्शन ऑब्जेक्ट। |

### रिटर्न वैल्यू

ScopedGuard क्लास की नई इंस्टेंस

## देखें

* संरचना [ScopeGuard](../scopeguard/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)