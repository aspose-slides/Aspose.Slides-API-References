---
title: SmartPtrInfo
second_title: Aspose.Slides for C++ API संदर्भ
description: सेवा वर्ग जो SmartPtr की सामग्री का परीक्षण और परिवर्तन करता है बिना अंतिम प्रकार जाने। गार्बेज कलेक्शन और लूप रेफरेंसेस का पता लगाने आदि के लिए उपयोग किया जाता है। इसे 'pointer to pointer' की तरह समझें। हम SmartPtr के बेस टाइप का उपयोग नहीं कर सकते क्योंकि उसका कोई बेस टाइप नहीं है; इसके बजाय हम इस 'info' वर्ग का उपयोग करते हैं।
type: docs
weight: 1249
url: /hi/system/smartptrinfo/
---
## SmartPtrInfo वर्ग

सेवा वर्ग जो [SmartPtr](../smartptr/) की सामग्री को अंतिम प्रकार के बिना परीक्षण और परिवर्तन करता है। गार्बेज कलेक्शन और लूप संदर्भों का पता लगाने आदि के लिए उपयोग किया जाता है। इसे 'pointer to pointer' की तरह समझें। हम [SmartPtr](../smartptr/) का बेस टाइप उपयोग नहीं कर सकते क्योंकि उसके पास कोई नहीं है; इसके बजाय हम इस 'info' वर्ग का उपयोग करते हैं।

```cpp
class SmartPtrInfo
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | उस कच्चे ऑब्जेक्ट को प्राप्त करता है जिसकी ओर संदर्भित पॉइंटर इंगित करता है। |
| [Object](../object/) * [getObject](./getobject/)() const | उस ऑब्जेक्ट को प्राप्त करता है जिसकी ओर संदर्भित पॉइंटर इंगित करता है। |
| [Object](../object/) * [getOwned](./getowned/)() const | ऑब्जेक्ट के स्वामित्व वाले पॉइंटर को प्राप्त करता है। |
|  [operator bool](./operator_bool/)() const | जाँचता है कि क्या info ऑब्जेक्ट गैर-शून्य पॉइंटर की ओर संकेत करता है। |
| **bool** [operator!](./operator_not/)() const | जाँचता है कि क्या info ऑब्जेक्ट गैर-शून्य पॉइंटर की ओर नहीं संकेत करता है। |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | संदर्भित पॉइंटर द्वारा इंगित [Object](../object/) की विधियों को कॉल करने की अनुमति देता है। |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | दो info ऑब्जेक्ट द्वारा संदर्भित पॉइंटर्स के मानों की कम-तुलना करता है। |
|  [SmartPtrInfo](./smartptrinfo/)() | खाली [SmartPtrInfo](./) ऑब्जेक्ट बनाता है। |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | निर्दिष्ट [SmartPtrInfo](./) ऑब्जेक्ट बनाता है जिसमें विशिष्ट स्मार्ट पॉइंटर की जानकारी होती है। |
## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)