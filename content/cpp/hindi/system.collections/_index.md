---
title: "System::Collections"
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 300
url: /hi/system.collections/
---
## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) बिट्स का जो इंडेक्स द्वारा संबोधित किए जा सकते हैं। इस क्लास की वस्तुएँ केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित की जानी चाहिए। इस प्रकार का इंस्टैंस कभी स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ होंगी। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें। |
| [BitArrayPtr](./bitarrayptr/) | [BitArray](./bitarray/) के लिए पॉइंटर। यह प्रकार अन्य ऑब्जेक्ट की डिलीशन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को या तो वैल्यू द्वारा या कॉन्स्ट रेफ़रेंस द्वारा पास किया जाना चाहिए। |
| [CollectionBase](./collectionbase/) | एक स्ट्रॉन्गली टाइप्ड कलेक्शन के लिए एब्स्ट्रैक्ट बेस क्लास प्रदान करता है। |
| [ICollection](./icollection/) | नॉन जेनरिक कलेक्शन इंटरफ़ेस को परिभाषित करता है। |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) सभी उन नॉन-जेनरिक कलेक्शनों के लिए बेस इंटरफ़ेस है जिन्हें एने्यूमरेट किया जा सकता है। |
| [IEnumerator](./ienumerator/) | एक एने्यूमरेटर का इंटरफ़ेस जो कुछ तत्वों के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टैंस कभी स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें। |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | रैपर जो जेनरिक Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) के ऊपर नॉन जेनरिक [IEnumerator](./ienumerator/) इम्प्लीमेंटेशन बनाता है - रेफ़रेंस टाइप्स के लिए रैपर। |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | रैपर जो जेनरिक Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) के ऊपर नॉन जेनरिक [IEnumerator](./ienumerator/) इम्प्लीमेंटेशन बनाता है - वैल्यू टाइप्स के लिए रैपर। |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) इंडेक्स द्वारा व्यक्तिगत रूप से एक्सेस की जा सकने वाली ऑब्जेक्ट्स की नॉन-जेनरिक कलेक्शन का प्रतिनिधित्व करता है। |
| [IListImplRefType](./ilistimplreftype/) | [System::Collections::Generic::List](../system.collections.generic/list/) ऑब्जेक्ट पर [System::Collections::IList](./ilist/) इंटरफ़ेस को लागू करने वाला स्टब। रेफ़रेंस टाइप्स के लिए इम्प्लीमेंटेशन। |
| [IListImplValueType](./ilistimplvaluetype/) | [System::Collections::Generic::List](../system.collections.generic/list/) ऑब्जेक्ट पर [System::Collections::IList](./ilist/) इंटरफ़ेस को लागू करने वाला स्टब। वैल्यू टाइप्स के लिए इम्प्लीमेंटेशन। |
| [IListWrapper](./ilistwrapper/) | जनरिक से नॉन-जेनरिक कलेक्शन में कास्टिंग का समर्थन करने के लिए इंटरफ़ेस। |
| [Invalidatable](./invalidatable/) | एक क्लास जो [InvalidatableTracker](./invalidatabletracker/) ऑब्जेक्ट्स के माध्यम से इसके वंशजों की स्थिति को ट्रैक करना संभव बनाता है। |
| [InvalidatableTracker](./invalidatabletracker/) | एक क्लास जो [Invalidatable](./invalidatable/) ऑब्जेक्ट्स के ट्रैकर को लागू करता है। |