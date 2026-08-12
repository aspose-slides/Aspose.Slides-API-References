---
title: IEnumerator
second_title: "Aspose.Slides for C++ API संदर्भ"
description: "ऐसे एनोमरेटर का इंटरफ़ेस जो कुछ तत्वों के माध्यम से इटररेट करने के लिए उपयोग किया जा सकता है। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रन-टाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बन सकता है। हमेशा इस वर्ग को System::SmartPtr पोइंटर में लपेटें और इस पोइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 300
url: /hi/system.collections.generic/ienumerator/
---
## IEnumerator वर्ग

किसी तत्वों के माध्यम से इटररेट करने के लिए उपयोग किया जा सकने वाला एनोमरेटर का इंटरफ़ेस। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रन-टाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फंक्शन को तर्क के रूप में पास करने के लिए करें।

```cpp
template<typename T>class IEnumerator : public virtual System::IDisposable,
                                        public System::Details::EnumeratorBasedIterator<T>,
                                        protected System::Details::IteratorPointerUpdater<T, false>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तत्व प्रकार। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [IEnumerator](./) * [AsVirtualizedIterator](./asvirtualizediterator/)() | VirtualizedIterator वर्ग द्वारा उपयोग के लिए इटरेटर को तैयार करता है। |
| System::Details::VirtualizedIteratorBase\<T\> * [CloneIterator](./cloneiterator/)() const override | वर्तमान इटरेटर को क्लोन करता है। |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](./current/)() const | वर्तमान तत्व प्राप्त करता है। |
| virtual void [Dispose](../../system/idisposable/dispose/)() | कुछ नहीं करता। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [get_Current](./get_current/)() const | वर्तमान तत्व प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [IEnumerator](./ienumerator/)() |  |
| void [IncrementIterator](./incrementiterator/)() override | इटरेटर को एक कदम आगे ले जाता है। |
| void [InitializeIterator](./initializeiterator/)() override | पहली [MoveNext()](./movenext/) कॉल करता है और एनोमरेटर ऑब्जेक्ट को VirtualizedIterator द्वारा उपयोग के लिए तैयार करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [MarkOwnedByVirtualizedIterator](./markownedbyvirtualizediterator/)() | वर्चुअलाइज़्ड इटरेटर द्वारा स्वामित्व वाले एनोमरेटर को चिह्नित करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम बनाता है। |
| virtual **bool** [MoveNext](./movenext/)() | एनोमरेटर को अगले तत्व पर ले जाता है। यदि पहले कोई तत्व संदर्भित नहीं था, तो उपलब्ध पहले तत्व को संदर्भित करता है। यदि कंटेनर का अंत पहुँचा गया, तो कुछ नहीं करता। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना value type ऑब्जेक्ट को nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr केस के लिए विशेषीकृत संस्करण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग्स केस के लिए विशेषीकृत संस्करण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउंट को घटाता है। |
| virtual void [Reset](./reset/)() | एनोमरेटर को पहले तत्व से पहले की स्थिति पर रीसेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~IEnumerator](./~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ValueType](./valuetype/) | वैल्यू टाइप। |

## टिप्पणी

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // List-class का इंस्टेंस बनाएं।
  auto collection = MakeObject<List<int>>();

  // सूची को भरें।
  collection->Add(1);
  collection->Add(2);
  collection->Add(3);

  // सूची का एनोमरेटर प्राप्त करें।
  auto enumerator = collection->GetEnumerator();

  while (enumerator->MoveNext())
  {
    // वर्तमान तत्व प्राप्त करें और उसे प्रिंट करें।
    std::cout << enumerator->get_Current() << ' ';
  }

  // एनोमरेटर को रीसेट करें।
  enumerator->Reset();

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
1 2 3
*/
```

## देखें

* क्लास [IDisposable](../../system/idisposable/)
* नामस्थान [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)