---
title: Register()
second_title: Aspose.Slides for C++ API संदर्भ
description: रद्दीकरण का अनुरोध होने पर एक कॉलबैक को बुलाया जाएगा।
type: docs
weight: 40
url: /hi/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const विधि

जब रद्दीकरण का अनुरोध किया जाता है, तो एक कॉलबैक को बुलाया जाएगा।

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | रद्दीकरण का अनुरोध किए जाने पर चलाने के लिए Action<>। |

### वापसी मान

[CancellationTokenRegistration](../../cancellationtokenregistration/) ऑब्जेक्ट जिसे कॉलबैक को हटाने के लिए उपयोग किया जा सकता है।

## टिप्पणियाँ

यदि रद्दीकरण का अनुरोध पहले ही किया जा चुका है, तो कॉलबैक तुरंत बुलाया जाएगा।

कॉलबैक को संक्षिप्त और नॉन-ब्लॉकिंग होना चाहिए क्योंकि इसे [CancellationTokenSource](../../cancellationtokensource/) पर Cancel() कॉल करने वाली थ्रेड पर निष्पादित किया जाएगा।

## देखें

* Typedef [Action](../../../system/action/)
* क्लास [CancellationTokenRegistration](../../cancellationtokenregistration/)
* क्लास [CancellationToken](../)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)