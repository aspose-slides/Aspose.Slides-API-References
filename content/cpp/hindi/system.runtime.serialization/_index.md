---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 794
url: /hi/system.runtime.serialization/
---
## क्लासेस

| Class | Description |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) इंटरफ़ेस का बेस कार्यान्वयन दर्शाता है। |
| [IFormatterConverter](./iformatterconverter/) | [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) की एक इनस्टेंस और फ़ॉर्मेटर-प्रदान किए गए क्लास के बीच कनेक्शन प्रदान करता है, जो [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) के भीतर डेटा को पार्स करने के लिए सबसे उपयुक्त है। |
| [ISerializable](./iserializable/) | सीरियलाइज़ किया जा सकने वाले ऑब्जेक्ट का इंटरफ़ेस। इस क्लास के ऑब्जेक्ट केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किए जाने चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रन-टाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को फ़ंक्शन को आर्गुमेंट के रूप में पास करें। |
| [SerializationInfo](./serializationinfo/) | नामित फ़ील्ड्स का सेट रखता है जो सीरियलाइज़्ड ऑब्जेक्ट का प्रतिनिधित्व करता है। लागू नहीं किया गया है। इस क्लास के ऑब्जेक्ट केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किए जाने चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रन-टाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को फ़ंक्शन को आर्गुमेंट के रूप में पास करें। |
| [StreamingContext](./streamingcontext/) | StreamingContext-का उपयोग करने वाली अनूदित क्लासेज़ को संकलित करने के लिए डमी क्लास। इस क्लास की इंस्टेंस को [SmartPtr](../system/smartptr/) द्वारा प्रबंधित न करें, इन्हें केवल स्टैक पर आवंटित किया जाना चाहिए। |
## टाइपडिफ़

| Typedef | Description |
| --- | --- |
| [SerializationException](./serializationexception/) |  |