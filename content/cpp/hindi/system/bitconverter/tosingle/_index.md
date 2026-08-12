---
title: ToSingle()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट एरे से निर्दिष्ट इंडेक्स से शुरू करके चार बाइट्स को एकल-सटीकता वाले फ्लोटिंग पॉइंट मान में परिवर्तित करता है।
type: docs
weight: 131
url: /hi/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) विधि


निर्दिष्ट एरे से निर्दिष्ट इंडेक्स से शुरू करके चार बाइट्स को एकल-सटीकता वाले फ्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) जो परिवर्तन के लिए बाइट्स को शामिल करता है |
| startIndex | int | [Index](../../index/) एरे में वह इंडेक्स जहाँ से बाइट्स को परिवर्तन के लिए लेना शुरू किया जाता है |

### वापसी मान

परिवर्तन के परिणामस्वरूप प्राप्त एकल-सटीकता वाला फ्लोटिंग पॉइंट मान

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) विधि


निर्दिष्ट एरे से निर्दिष्ट इंडेक्स से शुरू करके चार बाइट्स को एकल-सटीकता वाले फ्लोटिंग पॉइंट मान में परिवर्तित करता है।

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView जो परिवर्तन के लिए बाइट्स को शामिल करता है |
| startIndex | int | [Index](../../index/) एरे में वह इंडेक्स जहाँ से बाइट्स को परिवर्तन के लिए लेना शुरू किया जाता है |

### वापसी मान

परिवर्तन के परिणामस्वरूप प्राप्त एकल-सटीकता वाला फ्लोटिंग पॉइंट मान

## देखें भी

* टाइप्डेफ़ [ArrayPtr](../../arrayptr/)
* क्लास [BitConverter](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)