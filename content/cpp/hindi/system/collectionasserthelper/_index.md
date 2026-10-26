---
title: CollectionAssertHelper
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: कलेक्शन-संबंधित ऑपरेशनों के लिए Heler API।
type: docs
weight: 1548
url: /hi/system/collectionasserthelper/
---
## CollectionAssertHelper struct

Heler API for collection-related operations.

```cpp
class CollectionAssertHelper
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | सभी कलेक्शन तत्व प्रेडिकेट का पालन करते हैं, यह जाँचता है। |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | कोई भी कलेक्शन तत्व प्रेडिकेट का पालन करता है, यह जाँचता है। |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | संदेश प्रतिनिधित्व के लिए दो कलेक्शन को सीरियलाइज़ करता है। |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | तत्वों के स्ट्रिंग प्रतिनिधित्वों को जोड़कर कलेक्शन को स्ट्रिंग में परिवर्तित करता है। |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | दो कलेक्शन के बीच 'diff' की गणना करता है। प्रत्येक कलेक्शन के प्रत्येक तत्व को कुंजी के रूप में लेते हुए परिणामस्वरूप मान सकारात्मक होगा यदि तत्व \"expected\" कलेक्शन में अधिक बार उपस्थित हो, नकारात्मक यदि तत्व \"actual\" कलेक्शन में अधिक बार उपस्थित हो, और शून्य यदि प्रत्येक कलेक्शन में तत्व समान संख्या में उपस्थित हों। |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | स्ट्रिंग को संदेश पाठ के रूप में उपयोग करने के लिए स्वरूपित करता है। |
## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)