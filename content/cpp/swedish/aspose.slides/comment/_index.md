---
title: Comment
second_title: Aspose.Slides för C++ API-referens
description: Representerar en kommentar på en bild.
type: docs
weight: 417
url: /sv/aspose.slides/comment/
---
## Kommentar-klass

Representerar en kommentar på en bild.

```cpp
class Comment : public virtual Aspose::Slides::IComment,
                public Aspose::Slides::IDOMObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](./get_author/)() override | Returnerar författaren till en kommentar. Skrivskyddad [ICommentAuthor](../icommentauthor/). |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Returnerar tidpunkten för när kommentaren skapades. Att sätta denna egenskap till [DateTime::MinValue](../../system/datetime/minvalue/) betyder att ingen kommentar-tid är angiven. Läs [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](./get_parentcomment/)() override | Hämtar överordnad kommentar. Läs [IComment](../icomment/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](./get_position/)() override | Returnerar positionen för en kommentar på en bild. Läs [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)() override | Returnerar den överordnade bilden för en kommentar. Skrivskyddad [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | Returnerar den rena texten för en bildkommentar. Läs [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-uttrycket. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför en värdetyp-objekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| void [Remove](./remove/)() override | Tar bort kommentaren och alla dess svar från föräldrakollektionen. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Anger tidpunkten för när kommentaren skapades. Att sätta denna egenskap till [DateTime::MinValue](../../system/datetime/minvalue/) betyder att ingen kommentar-tid är angiven. Skriv [System::DateTime](../../system/datetime/). |
| void [set_ParentComment](./set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | Anger överordnad kommentar. Skriv [IComment](../icomment/). |
| void [set_Position](./set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Anger positionen för en kommentar på en bild. Skriv [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | Anger den rena texten för en bildkommentar. Skriv [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Anger det n:te mall-argumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning enligt C# lock()-uttrycket för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar

Det här exemplet visar hur du lägger till en kommentar på en bild i en PowerPoint-presentation. 
```cpp
// Instansierar Presentation-klassen
auto presentation = System::MakeObject<Presentation>();

// Lägger till en tom bild
presentation->get_Slides()->AddEmptySlide(presentation->get_LayoutSlides()->idx_get(0));
// Lägger till en författare
auto author = presentation->get_CommentAuthors()->AddAuthor(u"Jawad", u"MF");
// Ställer in positionen för kommentarer
System::Drawing::PointF point(0.2f, 0.2f);
// Lägger till bildkommentar för en författare på bild 1
author->get_Comments()->AddComment(u"Hello Jawad, this is slide comment", presentation->get_Slides()->idx_get(0), point, System::DateTime::get_Now());
// Lägger till bildkommentar för en författare på bild 2
author->get_Comments()->AddComment(u"Hello Jawad, this is second slide comment", presentation->get_Slides()->idx_get(1), point, System::DateTime::get_Now());
// Spara PowerPoint-presentationen
presentation->Save(u"Comments_out.pptx", SaveFormat::Pptx);
```
Det här exemplet visar hur du kommer åt en befintlig kommentar på en bild i en PowerPoint-presentation. 
```cpp
// Instansierar Presentation-klassen
auto presentation = System::MakeObject<Presentation>(u"Comments1.pptx");

// Iterera CommentAuthors
for (CommentAuthor&& commentAuthor : presentation->get_CommentAuthors())
{
    // Iterera Comments
    for (Comment&& comment : commentAuthor->get_Comments())
    {
        System::Console::WriteLine(System::String(u"ISlide :") + comment->get_Slide()->get_SlideNumber() +
                                   u" has comment: " + comment->get_Text() +
                                   u" with Author: " + comment->get_Author()->get_Name() +
                                   u" posted on time :" + comment->get_CreatedTime() + u"\n");
    }
}
```
Det här exemplet visar hur du lägger till kommentarer och får svar på dem. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
System::Drawing::PointF pos(10.0f, 10.0f);

// Adds a comment
System::SharedPtr<ICommentAuthor> author1 = pres->get_CommentAuthors()->AddAuthor(u"Author_1", u"A.A.");
System::SharedPtr<IComment> comment1 = author1->get_Comments()->AddComment(u"comment1", slide, pos, System::DateTime::get_Now());
// Adds a reply to comment1
System::SharedPtr<ICommentAuthor> author2 = pres->get_CommentAuthors()->AddAuthor(u"Autror_2", u"B.B.");
System::SharedPtr<IComment> reply1 = author2->get_Comments()->AddComment(u"reply 1 for comment 1", slide, pos, System::DateTime::get_Now());
reply1->set_ParentComment(comment1);
// Adds another reply to comment1
System::SharedPtr<IComment> reply2 = author2->get_Comments()->AddComment(u"reply 2 for comment 1", slide, pos, System::DateTime::get_Now());
reply2->set_ParentComment(comment1);
// Adds a reply to existing reply
System::SharedPtr<IComment> subReply = author1->get_Comments()->AddComment(u"subreply 3 for reply 2", slide, pos, System::DateTime::get_Now());
subReply->set_ParentComment(reply2);
System::SharedPtr<IComment> comment2 = author2->get_Comments()->AddComment(u"comment 2", slide, pos, System::DateTime::get_Now());
System::SharedPtr<IComment> comment3 = author2->get_Comments()->AddComment(u"comment 3", slide, pos, System::DateTime::get_Now());
System::SharedPtr<IComment> reply3 = author1->get_Comments()->AddComment(u"reply 4 for comment 3", pres->get_Slides()->idx_get(0), pos, System::DateTime::get_Now());
reply3->set_ParentComment(comment3);

// Displays the comments hierarchy on console
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
// Removes comment1 and all replies to it
comment1->Remove();
pres->Save(u"remove_comment.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [IComment](../icomment/)
* Klass [IDOMObject](../idomobject/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)