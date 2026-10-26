---
title: IModernComment
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।
type: docs
weight: 2965
url: /hi/aspose.slides/imoderncomment/
---
## IModernComment क्लास


स्लाइड पर एक टिप्पणी का प्रतिनिधित्व करता है।

```cpp
class IModernComment : public virtual Aspose::Slides::IComment
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) कार्यशैली का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजन के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../icomment/get_author/)() | एक टिप्पणी के लेखक को लौ टाता है। केवल पढ़ने योग्य [ICommentAuthor](../icommentauthor/)। |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](../icomment/get_createdtime/)() | एक टिप्पणी के निर्माण समय को लौ टाता है। इस गुण को [DateTime::MinValue](../../system/datetime/minvalue/) पर सेट करने का अर्थ है कि टिप्पणी का समय निर्धारित नहीं है। पढ़ें [System::DateTime](../../system/datetime/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../icomment/get_parentcomment/)() | पैरेंट टिप्पणी प्राप्त करता है। पढ़ें [IComment](../icomment/)। |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../icomment/get_position/)() | स्लाइड पर टिप्पणी की स्थिति लौ टाता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() | टिप्पणी से सम्बंधित एक आकार लौ टाता है। केवल पढ़ने योग्य [IShape](../ishape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../icomment/get_slide/)() | टिप्पणी की पैरेंट स्लाइड लौ टाता है। केवल पढ़ने योग्य [ISlide](../islide/)। |
| virtual [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() | टिप्पणी की स्थिति लौ टाता है। पढ़ें [ModernCommentStatus](../moderncommentstatus/)। |
| virtual [System::String](../../system/string/) [get_Text](../icomment/get_text/)() | स्लाइड टिप्पणी का सादा पाठ लौ टाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() | यदि टिप्पणी [AutoShape](../autoshape/) से सम्बंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई लौ टाता है। पढ़ें **int32_t**। |
| virtual **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() | यदि टिप्पणी [AutoShape](../autoshape/) से सम्बंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की प्रारंभिक स्थिति लौ टाता है। पढ़ें **int32_t**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से सम्बंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समानांतर। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया वस्तु प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया वस्तु प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार की वस्तु की रेफ़रेंस की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामलों के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषण। |
| virtual void [Remove](../icomment/remove/)() | टिप्पणी और उसकी सभी प्रतिक्रियाओं को पैरेंट संग्रह से हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउण्ट को घटाता है। |
| virtual void [set_CreatedTime](../icomment/set_createdtime/)([System::DateTime](../../system/datetime/)) | टिप्पणी के निर्माण समय को सेट करता है। इस गुण को [DateTime::MinValue](../../system/datetime/minvalue/) पर सेट करने का अर्थ है कि टिप्पणी का समय निर्धारित नहीं है। लिखें [System::DateTime](../../system/datetime/)। |
| virtual void [set_ParentComment](../icomment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) | पैरेंट टिप्पणी सेट करता है। लिखें [IComment](../icomment/)। |
| virtual void [set_Position](../icomment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | स्लाइड पर टिप्पणी की स्थिति सेट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| virtual void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) | टिप्पणी की स्थिति सेट करता है। लिखें [ModernCommentStatus](../moderncommentstatus/)। |
| virtual void [set_Text](../icomment/set_text/)([System::String](../../system/string/)) | स्लाइड टिप्पणी का सादा पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) | यदि टिप्पणी [AutoShape](../autoshape/) से सम्बंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की लंबाई सेट करता है। लिखें **int32_t**। |
| virtual void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) | यदि टिप्पणी [AutoShape](../autoshape/) से सम्बंधित है तो टेक्स्ट फ्रेम में टेक्स्ट चयन की प्रारंभिक स्थिति सेट करता है। लिखें **int32_t**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर सेट करें (shared के बजाय)। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउण्ट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पोइन्टर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउण्ट को घटाता है और लौ टाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पोइन्टर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समानांतर। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउण्ट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पोइन्टर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउण्ट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पोइन्टर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टिप्पणी



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## देखें

* क्लास [IComment](../icomment/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)