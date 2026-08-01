---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een manager voor die je in staat stelt placeholders aan de layout-dia toe te voegen.
type: docs
weight: 2627
url: /nl/aspose.slides/ilayoutplaceholdermanager/
---
## ILayoutPlaceholderManager klasse


Stelt een manager voor die je in staat stelt placeholders aan de layout-dia toe te voegen.

```cpp
class ILayoutPlaceholderManager : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddChartPlaceholder](./addchartplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om een grafiek te bevatten. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddContentPlaceholder](./addcontentplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddMediaPlaceholder](./addmediaplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om een media-object te bevatten. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddOnlineImagePlaceholder](./addonlineimageplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om een online-afbeelding te bevatten. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddPicturePlaceholder](./addpictureplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om een afbeelding te bevatten. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddSmartArtPlaceholder](./addsmartartplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om een [SmartArt](../../aspose.slides.smartart/) diagram te bevatten. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTablePlaceholder](./addtableplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om een tabel te bevatten. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTextPlaceholder](./addtextplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om tekstinhoud te bevatten. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalContentPlaceholder](./addverticalcontentplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om inhoud te bevatten, zoals een afbeelding, tabel, media of tekst in een verticale richting. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalTextPlaceholder](./addverticaltextplaceholder/)(**float**, **float**, **float**, **float**) | Voegt een nieuw placeholder-shape toe aan de layout-dia om tekstinhoud in een verticale richting te bevatten. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommapuntenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommapuntenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of object een instantie van het type beschreven door targetType vertegenwoordigt. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe dat pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)