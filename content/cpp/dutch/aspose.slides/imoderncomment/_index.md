---
title: IModernComment
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een opmerking op een dia voor.
type: docs
weight: 2965
url: /nl/aspose.slides/imoderncomment/
---
## IModernComment klasse


Stelt een opmerking op een dia voor.

```cpp
class IModernComment : public virtual Aspose::Slides::IComment
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../icomment/get_author/)() | Retourneert de auteur van een opmerking. Alleen-lezen [ICommentAuthor](../icommentauthor/). |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](../icomment/get_createdtime/)() | Retourneert de tijd van het maken van een opmerking. Als deze eigenschap wordt ingesteld op [DateTime::MinValue](../../system/datetime/minvalue/) betekent dit dat er geen opmerkingstijd is ingesteld. Lezen [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../icomment/get_parentcomment/)() | Haalt bovenliggende opmerking op. Lezen [IComment](../icomment/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../icomment/get_position/)() | Retourneert de positie van een opmerking op een dia. Lezen [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() | Retourneert een vorm die aan de opmerking is gekoppeld. Alleen-lezen [IShape](../ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../icomment/get_slide/)() | Retourneert de bovenliggende dia van een opmerking. Alleen-lezen [ISlide](../islide/). |
| virtual [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() | Retourneert de status van de opmerking. Lezen [ModernCommentStatus](../moderncommentstatus/). |
| virtual [System::String](../../system/string/) [get_Text](../icomment/get_text/)() | Retourneert de platte tekst van een dia-opmerking. Lezen [System::String](../../system/string/). |
| virtual **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() | Retourneert de lengte van de tekstreeks in het tekstkader als de opmerking is gekoppeld aan [AutoShape](../autoshape/). Lezen **int32_t**. |
| virtual **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() | Retourneert de startpositie van de tekstreeks in het tekstkader als de opmerking is gekoppeld aan [AutoShape](../autoshape/). Lezen **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde van waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| virtual void [Remove](../icomment/remove/)() | Verwijdert de opmerking en al zijn antwoorden uit de bovenliggende verzameling. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_CreatedTime](../icomment/set_createdtime/)([System::DateTime](../../system/datetime/)) | Stelt de tijd van het maken van een opmerking in. Als deze eigenschap wordt ingesteld op [DateTime::MinValue](../../system/datetime/minvalue/) betekent dit dat er geen opmerkingstijd is ingesteld. Schrijven [System::DateTime](../../system/datetime/). |
| virtual void [set_ParentComment](../icomment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) | Stelt bovenliggende opmerking in. Schrijven [IComment](../icomment/). |
| virtual void [set_Position](../icomment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Stelt de positie van een opmerking op een dia in. Schrijven [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) | Stelt de status van de opmerking in. Schrijven [ModernCommentStatus](../moderncommentstatus/). |
| virtual void [set_Text](../icomment/set_text/)([System::String](../../system/string/)) | Stelt de platte tekst van een dia-opmerking in. Schrijven [System::String](../../system/string/). |
| virtual void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) | Stelt de lengte van de tekstreeks in het tekstkader in als de opmerking gekoppeld is aan [AutoShape](../autoshape/). Schrijven **int32_t**. |
| virtual void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) | Stelt de startpositie van de tekstreeks in het tekstkader in als de opmerking gekoppeld is aan [AutoShape](../autoshape/). Schrijven **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n-de sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |
## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Zie ook

* Klasse [IComment](../icomment/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)