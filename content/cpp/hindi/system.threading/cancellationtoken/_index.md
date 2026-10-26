---
title: CancellationToken
second_title: Aspose.Slides for C++ API संदर्भ
description: संचालन को रद्द करने की सूचना प्रसारित करता है। यह क्लास थ्रेड्स के बीच सहयोगात्मक रद्दीकरण के लिए एक तंत्र प्रदान करती है, जिससे एक थ्रेड अन्य थ्रेड्स को सूचित कर सकता है कि कोई ऑपरेशन रद्द किया जाना चाहिए।
type: docs
weight: 14
url: /hi/system.threading/cancellationtoken/
---
## CancellationToken क्लास

ऑपरेशनों को रद्द करने की सूचना को प्रसारित करता है। यह क्लास थ्रेड्स के बीच सहयोगात्मक रद्दीकरण के लिए एक तंत्र प्रदान करती है, जिससे एक थ्रेड अन्य थ्रेड्स को सूचित कर सकता है कि कोई ऑपरेशन रद्द किया जाना चाहिए।

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | जाँचता है कि यह टोकन रद्द स्थिति में रहने में सक्षम है या नहीं। |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | जाँचता है कि इस टोकन के लिए रद्दीकरण की अनुरोध किया गया है या नहीं। |
| static [CancellationToken](./) [get_None](./get_none/)() | एक खाली [System::Threading::CancellationToken](./) मान वापस करता है। |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | एक कॉलबैक पंजीकृत करता है जिसे रद्दीकरण के अनुरोध पर बुलाया जाएगा। |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | यदि रद्दीकरण का अनुरोध किया गया है तो OperationCanceledException फेंकता है। |

## टिप्पणी

एक [CancellationToken](./) केवल उसके संबंधित [CancellationTokenSource](../cancellationtokensource/) के माध्यम से रद्द किया जा सकता है।

## देखें

* नेमस्पेस [System::Threading](../)
* लाइब्रेरी [Aspose.Slides](../../)