---
title: Font
second_title: Aspose.Slides for C++ API संदर्भ
description: "पाठ के लिए एक विशिष्ट फ़ॉर्मेट का प्रतिनिधित्व करता है, जिसमें फ़ॉन्ट फ़ेस, आकार और शैली शामिल हैं। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टैंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फंक्शनों को आर्ग्युमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 79
url: /hi/system.drawing/font/
---
## फ़ॉन्ट क्लास

Represents a particular format for text, including font face, size, and style. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Font : public System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | वर्तमान फ़ॉन्ट की एक प्रति लौटाता है। |
| void [Dispose](./dispose/)() | वर्तमान ऑब्जेक्ट द्वारा अधिग्रहित सभी ऑपरेटिंग सिस्टम संसाधनों को रिलीज़ करता है। |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्धारित करता है कि वर्तमान और निर्दिष्ट ऑब्जेक्ट समान हैं या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | निर्दिष्ट मौजूदा फ़ॉन्ट को निर्दिष्ट फ़ॉन्ट स्टाइल के साथ दर्शाने वाले [Font](./) क्लास की नई इंस्टेंस बनाता है। |
| [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | [Font](./) क्लास की नई इंस्टेंस बनाता है। |
| [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | [Font](./) क्लास की नई इंस्टेंस बनाता है। |
| [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | [Font](./) क्लास की नई इंस्टेंस बनाता है। |
| [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | [Font](./) क्लास की नई इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | लागू नहीं किया गया। |
| **bool** [get_Bold](./get_bold/)() | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया फ़ॉन्ट बोल्ड शैली लागू है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट का फ़ॉन्ट फ़ैमिली लौटाता है। |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की शैली लौटाता है। |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | एक मान लौटाता है जो दर्शाता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट में उपयोग किया गया GDI कैरेक्टर सेट कौन सा है। |
| int [get_Height](./get_height/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की लाइन स्पेसिंग पिक्सेल में लौटाता है। |
| **bool** [get_Italic](./get_italic/)() | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया फ़ॉन्ट इटैलिक शैली लागू है या नहीं। |
| [String](../../system/string/) [get_Name](./get_name/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट का फेस नाम लौटाता है। |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | फ़ॉन्ट के मूल रूप से निर्दिष्ट नाम को लौटाता है। |
| **float** [get_Size](./get_size/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट का एम आकार, यूनिट प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में मापा गया, लौटाता है। |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट का एम आकार पॉइंट्स में लौटाता है। |
| **bool** [get_Strikeout](./get_strikeout/)() | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया फ़ॉन्ट स्ट्राइकआउट शैली लागू है या नहीं। |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की शैली लौटाता है। |
| **bool** [get_Underline](./get_underline/)() | निर्धारित करता है कि वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया फ़ॉन्ट अंडरलाइन शैली लागू है या नहीं। |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की माप इकाई लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की लाइन स्पेसिंग, निर्दिष्ट [Graphics](../graphics/) ऑब्जेक्ट की वर्तमान इकाई में लौटाता है। |
| **float** [GetHeight](./getheight/)(**float**) | निर्दिष्ट ऊर्ध्वाधर रिजॉल्यूशन वाले डिस्प्ले डिवाइस पर रेंडर किए जाने पर वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए फ़ॉन्ट की ऊँचाई लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांच करता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को वीकम पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर को वीकम मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीकम रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीकम रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Drawing](../)
* लाइब्रेरी [Aspose.Slides](../../)