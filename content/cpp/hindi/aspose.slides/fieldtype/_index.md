---
title: FieldType
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़ील्ड का एक प्रकार दर्शाता है। यह मान निर्धारित करता है कि अद्यतन होने पर फ़ील्ड भाग में कौन सा टेक्स्ट सेट किया जाएगा।
type: docs
weight: 872
url: /hi/aspose.slides/fieldtype/
---
## FieldType क्लास

फ़ील्ड का प्रकार दर्शाता है। यह मान निर्धारित करता है कि फ़ील्ड हिस्से को अपडेट होने पर कौन से पाठ को सेट किया जाएगा।

```cpp
class FieldType : public Aspose::Slides::IFieldType
```

## विधियां

| मेथड | विवरण |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | जाँचता है कि यह फ़ील्ड किसी अन्य के बराबर है या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [FieldType](./fieldtype/)([System::String](../../system/string/)) | नए उदाहरण को प्रारम्भ करता है [FieldType](./) क्लास का। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime](./get_datetime/)() | रेंडरिंग एप्लिकेशन के लिए डिफ़ॉल्ट डेट टाइम फॉर्मेट में वर्तमान तिथि और समय। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime1](./get_datetime1/)() | वर्तमान तिथि और समय को पहले पूर्वनिर्धारित फॉर्मेट (MM/DD/YYYY for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime10](./get_datetime10/)() | वर्तमान तिथि और समय को दसवें पूर्वनिर्धारित फॉर्मेट (hh:mm for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime11](./get_datetime11/)() | वर्तमान तिथि और समय को ग्यारहवें पूर्वनिर्धारित फॉर्मेट (hh:mm:ss for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime12](./get_datetime12/)() | वर्तमान तिथि और समय को बारहवें पूर्वनिर्धारित फॉर्मेट (hh:mm AM/PM for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime13](./get_datetime13/)() | वर्तमान तिथि और समय को तेरहवें पूर्वनिर्धारित फॉर्मेट (hh:mm:ss AM/PM for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime2](./get_datetime2/)() | वर्तमान तिथि और समय को दूसरे पूर्वनिर्धारित फॉर्मेट (Day, Month DD, YYYY for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime3](./get_datetime3/)() | वर्तमान तिथि और समय को तीसरे पूर्वनिर्धारित फॉर्मेट (DD Month YYYY for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime4](./get_datetime4/)() | वर्तमान तिथि और समय को चौथे पूर्वनिर्धारित फॉर्मेट (Month DD, YYYY for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime5](./get_datetime5/)() | वर्तमान तिथि और समय को पाँचवें पूर्वनिर्धारित फॉर्मेट (DD-Mon-YY for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime6](./get_datetime6/)() | वर्तमान तिथि और समय को छठे पूर्वनिर्धारित फॉर्मेट (Month YY for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime7](./get_datetime7/)() | वर्तमान तिथि और समय को सातवें पूर्वनिर्धारित फॉर्मेट (Mon-YY for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime8](./get_datetime8/)() | वर्तमान तिथि और समय को आठवें पूर्वनिर्धारित फॉर्मेट (MM/DD/YYYY hh:mm AM/PM for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime9](./get_datetime9/)() | वर्तमान तिथि और समय को नौवें पूर्वनिर्धारित फॉर्मेट (MM/DD/YYYY hh:mm:ss AM/PM for english) में देता है। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Footer](./get_footer/)() | [Slide](../slide/) का फुटर। केवल-पढ़ने योग्य [FieldType](./)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Header](./get_header/)() | [Slide](../slide/) का हेडर। केवल-पढ़ने योग्य [FieldType](./)। |
| [System::String](../../system/string/) [get_InternalString](./get_internalstring/)() override | इस [FieldType](./) ऑब्जेक्ट का आंतरिक नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_SlideNumber](./get_slidenumber/)() | वर्तमान स्लाइड का क्रमांक। केवल-पढ़ने योग्य [FieldType](./)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | इस ऑब्जेक्ट का हैशकोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारम्भ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासेस की कॉपी कन्स्ट्रक्शन को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासेस की कॉपी कन्स्ट्रक्शन को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_InternalString](./set_internalstring/)([System::String](../../system/string/)) override | इस [FieldType](./) ऑब्जेक्ट का आंतरिक नाम लौटाता है। लिखें [System::String](../../system/string/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें भी

* क्लास [IFieldType](../ifieldtype/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)