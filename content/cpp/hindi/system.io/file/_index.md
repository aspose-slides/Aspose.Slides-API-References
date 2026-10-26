---
title: File
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़ाइलों को संशोधित करने के लिए मेथड्स प्रदान करता है। यह एक स्थिर प्रकार है जिसमें कोई instance सेवाएँ नहीं हैं। आपको किसी भी माध्यम से इसकी instance नहीं बनानी चाहिए।
type: docs
weight: 261
url: /hi/system.io/file/
---
## File क्लास

फ़ाइलों को संशोधित करने के लिए मेथड्स प्रदान करता है। यह एक static प्रकार है जिसमें कोई instance सेवाएँ नहीं हैं। आपको किसी भी माध्यम से इसकी इंस्टेंस बनानी नहीं चाहिए।

```cpp
class File
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट स्ट्रिंग संग्रह से स्ट्रिंग्स को निर्दिष्ट फ़ाइल में निर्दिष्ट एन्कोडिंग का उपयोग करके प्रत्येक स्ट्रिंग को नई पंक्ति में लिखते हुए जोड़ता है। यदि निर्दिष्ट फ़ाइल मौजूद नहीं है, तो इसे बनाया जाता है। सभी स्ट्रिंग्स लिखने के बाद फ़ाइल बंद हो जाती है। |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट स्ट्रिंग को निर्दिष्ट फ़ाइल में निर्दिष्ट एन्कोडिंग का उपयोग करके जोड़ता है। |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | एक [StreamWriter](../streamwriter/) ऑब्जेक्ट बनाता है जो UTF-8 एन्कोडिंग का उपयोग करके निर्दिष्ट फ़ाइल में टेक्स्ट जोड़ता है। यदि निर्दिष्ट फ़ाइल मौजूद नहीं है, तो इसे बनाया जाता है। |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | निर्दिष्ट फ़ाइल को निर्दिष्ट स्थान पर कॉपी करता है। यदि गंतव्य फ़ाइल पहले से मौजूद है, तो एक पैरामीटर यह निर्धारित करता है कि क्या इसे अधिलेखित किया जाना चाहिए। |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | एक नई फ़ाइल (या मौजूदा को अधिलेखित) बनाता है और इसे निर्दिष्ट बफ़र आकार और विकल्पों का उपयोग करके पढ़ने और लिखने के लिए खोलता है। |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | UTF-8 एन्कोडेड टेक्स्ट लिखने के लिए नई फ़ाइल बनाता है या मौजूदा को खोलता है। |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | लागू नहीं किया गया। |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइल या डायरेक्टरी को हटाता है। |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | लागू नहीं किया गया। |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | निर्धारित करता है कि निर्धारित पथ मौजूदा फ़ाइल को संदर्भित करता है या नहीं। |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई के गुण लौटाता है। |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का निर्माण समय स्थानीय समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का निर्माण समय UTC समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का अंतिम पहुँच समय स्थानीय समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का अंतिम पहुँच समय UTC समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का अंतिम लिखने का समय स्थानीय समय के रूप में लौटाता है। |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | निर्दिष्ट इकाई का अंतिम लिखने का समय UTC समय के रूप में लौटाता है। |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइल को नई स्थान पर ले जाता है। |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | निर्दिष्ट फ़ाइल को निर्दिष्ट मोड में पढ़ने और लिखने के लिए खोलता है और बिना शेयरिंग के। |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | निर्दिष्ट फ़ाइल को निर्दिष्ट मोड में, निर्दिष्ट एक्सेस प्रकार और शेयरिंग विकल्प के साथ खोलता है। |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइल को केवल पढ़ने के लिए, 'Open' मोड में, पढ़ने के लिए साझा एक्सेस के साथ खोलता है। |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | UTF-8 एन्कोडिंग का उपयोग करके टेक्स्ट पढ़ने के लिए निर्दिष्ट मौजूदा फ़ाइल को बिना शेयरिंग के खोलता है। |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | निर्दिष्ट फ़ाइल को केवल लिखने के लिए, 'OpenOrCreate' मोड में, बिना शेयरिंग के खोलता है। |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | निर्दिष्ट बाइनरी फ़ाइल की सामग्री को बाइट एरे में पढ़ता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट टेक्स्ट फ़ाइल की सामग्री को लाइन दर लाइन पढ़कर निर्दिष्ट कैरेक्टर एन्कोडिंग का उपयोग करके स्ट्रिंग्स की एरे में रखता है। |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट टेक्स्ट फ़ाइल की सामग्री को निर्दिष्ट कैरेक्टर एन्कोडिंग का उपयोग करके एकल [String](../../system/string/) ऑब्जेक्ट में पढ़ता है। |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट टेक्स्ट फ़ाइल की सामग्री को लाइन दर लाइन पढ़ता है, निर्दिष्ट कैरेक्टर एन्कोडिंग का उपयोग करके, और स्ट्रिंग्स का एक enumerable संग्रह लौटाता है, जिसमें से प्रत्येक फ़ाइल की सामग्री की एकल पंक्ति का प्रतिनिधित्व करता है। |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | एक फ़ाइल की सामग्री को दूसरी फ़ाइल से प्रतिस्थापित करता है और प्रतिस्थापित फ़ाइल का बैकअप बनाता है। |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | निर्दिष्ट फ़ाइल पर निर्दिष्ट गुण सेट करता है। |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | लागू नहीं किया गया। |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | लागू नहीं किया गया। |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | लागू नहीं किया गया। |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | लागू नहीं किया गया। |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | निर्दिष्ट इकाई का अंतिम लिखने का समय स्थानीय समय के रूप में सेट करता है। |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | निर्दिष्ट इकाई का अंतिम लिखने का समय UTC समय के रूप में सेट करता है। |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | निर्दिष्ट बाइनरी फ़ाइल को अधिलेखित करता है और निर्दिष्ट बाइट्स को इसमें लिखता है। |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | एक नई टेक्स्ट फ़ाइल बनाता है या मौजूदा को अधिलेखित करता है और सभी स्ट्रिंग्स को निर्दिष्ट enumerable संग्रह से नई पंक्तियों में, प्रत्येक स्ट्रिंग को नई पंक्ति में, निर्दिष्ट एन्कोडिंग का उपयोग करके लिखता है। |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | एक नई टेक्स्ट फ़ाइल बनाता है या मौजूदा को अधिलेखित करता है और निर्दिष्ट स्ट्रिंग्स की एरे से सभी स्ट्रिंग्स को नई पंक्तियों में, प्रत्येक स्ट्रिंग को नई पंक्ति में, निर्दिष्ट एन्कोडिंग का उपयोग करके लिखता है। |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | एक नई टेक्स्ट फ़ाइल बनाता है या मौजूदा को अधिलेखित करता है और निर्दिष्ट स्ट्रिंग की सामग्री को निर्दिष्ट एन्कोडिंग का उपयोग करके इसमें लिखता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | फ़ाइल से पढ़ने और लिखने के दौरान बफ़र किए गए बाइट्स की संख्या का डिफ़ॉल्ट मान। |

## देखें

* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)