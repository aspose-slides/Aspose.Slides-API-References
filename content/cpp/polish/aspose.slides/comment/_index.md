---
title: Comment
second_title: Aspose.Slides dla C++ – referencja API
description: Reprezentuje komentarz na slajdzie.
type: docs
weight: 417
url: /pl/aspose.slides/comment/
---
## Klasa Comment


Reprezentuje komentarz na slajdzie.

```cpp
class Comment : public virtual Aspose::Slides::IComment,
                public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](./get_author/)() override | Zwraca autora komentarza. Tylko do odczytu [ICommentAuthor](../icommentauthor/). |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Zwraca czas utworzenia komentarza. Ustawienie tej właściwości na [DateTime::MinValue](../../system/datetime/minvalue/) oznacza brak ustawionego czasu komentarza. Odczyt [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](./get_parentcomment/)() override | Pobiera komentarz nadrzędny. Odczyt [IComment](../icomment/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](./get_position/)() override | Zwraca pozycję komentarza na slajdzie. Odczyt [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)() override | Zwraca slajd nadrzędny komentarza. Tylko do odczytu [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | Zwraca zwykły tekst komentarza slajdu. Odczyt [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| void [Remove](./remove/)() override | Removes comment and all its replies from the parent collection. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Ustawia czas utworzenia komentarza. Ustawienie tej właściwości na [DateTime::MinValue](../../system/datetime/minvalue/) oznacza brak ustawionego czasu komentarza. Zapis [System::DateTime](../../system/datetime/). |
| void [set_ParentComment](./set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | Sets parent comment. Zapis [IComment](../icomment/). |
| void [set_Position](./set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Ustawia pozycję komentarza na slajdzie. Zapis [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | Ustawia zwykły tekst komentarza slajdu. Zapis [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |

## Uwagi


Ten przykład pokazuje, jak dodać komentarz do slajdu w prezentacji PowerPoint. 
```cpp
// Tworzy instancję klasy Presentation
auto presentation = System::MakeObject<Presentation>();

// Dodaje pusty slajd
presentation->get_Slides()->AddEmptySlide(presentation->get_LayoutSlides()->idx_get(0));
// Dodaje autora
auto author = presentation->get_CommentAuthors()->AddAuthor(u"Jawad", u"MF");
// Ustawia pozycję komentarzy
System::Drawing::PointF point(0.2f, 0.2f);
// Dodaje komentarz slajdu dla autora na slajdzie 1
author->get_Comments()->AddComment(u"Hello Jawad, this is slide comment", presentation->get_Slides()->idx_get(0), point, System::DateTime::get_Now());
// Dodaje komentarz slajdu dla autora na slajdzie 2
author->get_Comments()->AddComment(u"Hello Jawad, this is second slide comment", presentation->get_Slides()->idx_get(1), point, System::DateTime::get_Now());
// Zapisuje plik prezentacji PowerPoint
presentation->Save(u"Comments_out.pptx", SaveFormat::Pptx);
```
 Ten przykład pokazuje, jak uzyskać dostęp do istniejącego komentarza na slajdzie w prezentacji PowerPoint. 
```cpp
// Tworzy instancję klasy Presentation
auto presentation = System::MakeObject<Presentation>(u"Comments1.pptx");

// Iteruje po CommentAuthors
for (CommentAuthor&& commentAuthor : presentation->get_CommentAuthors())
{
    // Iteruje po Comments
    for (Comment&& comment : commentAuthor->get_Comments())
    {
        System::Console::WriteLine(System::String(u"ISlide :") + comment->get_Slide()->get_SlideNumber() +
                                   u" has comment: " + comment->get_Text() +
                                   u" with Author: " + comment->get_Author()->get_Name() +
                                   u" posted on time :" + comment->get_CreatedTime() + u"\n");
    }
}
```
 Ten przykład pokazuje, jak dodać komentarze i pobrać odpowiedzi na nie. 
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

## Zobacz także

* Klasa [IComment](../icomment/)
* Klasa [IDOMObject](../idomobject/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)