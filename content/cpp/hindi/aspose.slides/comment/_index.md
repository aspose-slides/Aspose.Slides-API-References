---
title: Comment
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड पर टिप्पणी का प्रतिनिधित्व करता है।
type: docs
weight: 417
url: /hi/aspose.slides/comment/
---
## Comment वर्ग

Represents a comment on a slide.

```cpp
class Comment : public virtual Aspose::Slides::IComment,
                public Aspose::Slides::IDOMObject
```

## विधियों

| Method | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](./get_author/)() override | टिप्पणी का लेखक लौटाता है। केवल-पढ़ने योग्य [ICommentAuthor](../icommentauthor/)। |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | टिप्पणी निर्माण का समय लौटाता है। इस प्रॉपर्टी को [DateTime::MinValue](../../system/datetime/minvalue/) सेट करने का अर्थ है कि कोई टिप्पणी समय सेट नहीं है। पढ़ें [System::DateTime](../../system/datetime/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](./get_parentcomment/)() override | माता-टिप्पणी प्राप्त करता है। पढ़ें [IComment](../icomment/)। |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](./get_position/)() override | स्लाइड पर टिप्पणी की स्थिति लौटाता है। पढ़ें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)() override | टिप्पणी की मूल स्लाइड लौटाता है। केवल-पढ़ने योग्य [ISlide](../islide/)। |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | स्लाइड टिप्पणी का साधारण पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानान्तर। कस्टम ऑब्जेक्ट की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानान्तर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानान्तर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानान्तर। कस्टम टाइप को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट को रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट को रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| void [Remove](./remove/)() override | टिप्पणी और उसकी सभी प्रतिक्रियाओं को पैरेंट कलेक्शन से हटा देता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | टिप्पणी निर्माण का समय सेट करता है। इस प्रॉपर्टी को [DateTime::MinValue](../../system/datetime/minvalue/) सेट करने का अर्थ है कि कोई टिप्पणी समय सेट नहीं है। लिखें [System::DateTime](../../system/datetime/)। |
| void [set_ParentComment](./set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | माता-टिप्पणी सेट करता है। लिखें [IComment](../icomment/)। |
| void [set_Position](./set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | स्लाइड पर टिप्पणी की स्थिति सेट करता है। लिखें [System::Drawing::PointF](../../system.drawing/pointf/)। |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | स्लाइड टिप्पणी का साधारण पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को इन्क्रीमेंट करता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को डिक्रीमेंट करता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानान्तर। कस्टम ऑब्जेक्ट को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को इन्क्रीमेंट करता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को डिक्रीमेंट करता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणियाँ

यह उदाहरण दर्शाता है कि आप PowerPoint प्रस्तुति में एक स्लाइड पर टिप्पणी कैसे जोड़ सकते हैं। 
```cpp
// Presentation क्लास का उदाहरण बनाता है
auto presentation = System::MakeObject<Presentation>();

// एक खाली स्लाइड जोड़ता है
presentation->get_Slides()->AddEmptySlide(presentation->get_LayoutSlides()->idx_get(0));
// एक लेखक जोड़ता है
auto author = presentation->get_CommentAuthors()->AddAuthor(u"Jawad", u"MF");
// टिप्पणी के लिए स्थिति सेट करता है
System::Drawing::PointF point(0.2f, 0.2f);
// स्लाइड 1 पर लेखक के लिए स्लाइड टिप्पणी जोड़ता है
author->get_Comments()->AddComment(u"Hello Jawad, this is slide comment", presentation->get_Slides()->idx_get(0), point, System::DateTime::get_Now());
// स्लाइड 2 पर लेखक के लिए स्लाइड टिप्पणी जोड़ता है
author->get_Comments()->AddComment(u"Hello Jawad, this is second slide comment", presentation->get_Slides()->idx_get(1), point, System::DateTime::get_Now());
// PowerPoint प्रस्तुति फ़ाइल को सहेजें
presentation->Save(u"Comments_out.pptx", SaveFormat::Pptx);
```
 यह उदाहरण दर्शाता है कि आप PowerPoint प्रस्तुति में एक स्लाइड पर मौजूदा टिप्पणी तक कैसे पहुँच सकते हैं। 
```cpp
// Presentation क्लास का उदाहरण बनाता है
auto presentation = System::MakeObject<Presentation>(u"Comments1.pptx");

// CommentAuthors को पुनरावृत्ति करता है
for (CommentAuthor&& commentAuthor : presentation->get_CommentAuthors())
{
    // Comments को पुनरावृत्ति करता है
    for (Comment&& comment : commentAuthor->get_Comments())
    {
        System::Console::WriteLine(System::String(u"ISlide :") + comment->get_Slide()->get_SlideNumber() +
                                   u" has comment: " + comment->get_Text() +
                                   u" with Author: " + comment->get_Author()->get_Name() +
                                   u" posted on time :" + comment->get_CreatedTime() + u"\n");
    }
}
```
 यह उदाहरण दर्शाता है कि आप टिप्पणी कैसे जोड़ सकते हैं और उनके जवाब कैसे प्राप्त कर सकते हैं। 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
System::Drawing::PointF pos(10.0f, 10.0f);

// एक टिप्पणी जोड़ता है
System::SharedPtr<ICommentAuthor> author1 = pres->get_CommentAuthors()->AddAuthor(u"Author_1", u"A.A.");
System::SharedPtr<IComment> comment1 = author1->get_Comments()->AddComment(u"comment1", slide, pos, System::DateTime::get_Now());
// टिप्पणी1 के लिए उत्तर जोड़ता है
System::SharedPtr<ICommentAuthor> author2 = pres->get_CommentAuthors()->AddAuthor(u"Autror_2", u"B.B.");
System::SharedPtr<IComment> reply1 = author2->get_Comments()->AddComment(u"reply 1 for comment 1", slide, pos, System::DateTime::get_Now());
reply1->set_ParentComment(comment1);
// टिप्पणी1 के लिए दूसरा उत्तर जोड़ता है
System::SharedPtr<IComment> reply2 = author2->get_Comments()->AddComment(u"reply 2 for comment 1", slide, pos, System::DateTime::get_Now());
reply2->set_ParentComment(comment1);
// मौजूदा उत्तर के लिए उत्तर जोड़ता है
System::SharedPtr<IComment> subReply = author1->get_Comments()->AddComment(u"subreply 3 for reply 2", slide, pos, System::DateTime::get_Now());
subReply->set_ParentComment(reply2);
System::SharedPtr<IComment> comment2 = author2->get_Comments()->AddComment(u"comment 2", slide, pos, System::DateTime::get_Now());
System::SharedPtr<IComment> comment3 = author2->get_Comments()->AddComment(u"comment 3", slide, pos, System::DateTime::get_Now());
System::SharedPtr<IComment> reply3 = author1->get_Comments()->AddComment(u"reply 4 for comment 3", pres->get_Slides()->idx_get(0), pos, System::DateTime::get_Now());
reply3->set_ParentComment(comment3);

// कन्सोल पर टिप्पणी पदानुक्रम दिखाता है
auto comments = slide->GetSlideComments(nullptr);
for (int32_t i = 0; i < comments->get_Length(); i++)
{
    System::SharedPtr<IComment> comment = comments[i];
    while (comment->get_ParentComment() != nullptr)
    {
        System::Console::Write(u"\t");
        comment = comment->get_ParentComment();
    }

    System::Console::Write(u"{0} : {1}", comments[i]->get_Author()->get_Name(), comments[i]->get_Text());
    System::Console::WriteLine();
}

pres->Save(u"parent_comment.pptx", SaveFormat::Pptx);
// टिप्पणी1 को और उसके सभी उत्तरों को हटाता है
comment1->Remove();
pres->Save(u"remove_comment.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* वर्ग [IComment](../icomment/)
* वर्ग [IDOMObject](../idomobject/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)