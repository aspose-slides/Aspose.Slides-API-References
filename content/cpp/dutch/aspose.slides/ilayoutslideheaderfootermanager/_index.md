---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides voor C++ API-referentie
description: Representeert een manager die het gedrag van de voettekst van de layout-dia, datum-tijd, paginanummer-plaatsaanduidingen en alle onderliggende plaatsaanduidingen bevat. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de layout-dia.
type: docs
weight: 2666
url: /nl/aspose.slides/ilayoutslideheaderfootermanager/
---
## ILayoutSlideHeaderFooterManager klasse

Representeert een manager die gedrag bevat van de layout-dia-voettekst, datum-tijd, paginanummer-plaatsaanduidingen en alle onderliggende plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de layout-dia.

```cpp
class ILayoutSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert een C#-achtige zwevende-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert een C#-achtige zwevende-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Krijgt een waarde die aangeeft dat er een datum-tijd-plaatsaanduiding aanwezig is. Lees **bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Krijgt een waarde die aangeeft dat er een voettekst-plaatsaanduiding aanwezig is. Lees **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Krijgt een waarde die aangeeft dat er een paginanummer-plaatsaanduiding aanwezig is. Lees **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Krijgt de referentieteller-datastructuur die aan het object gekoppeld is. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Krijgt het werkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Stelt tekst in voor de datum-tijd-plaatsaanduiding van de layout-dia en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de layout-dia. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Wijzigt de zichtbaarheid van de datum-tijd-plaatsaanduiding van de layout-dia en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de layout-dia. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Stelt tekst in voor de datum-tijd-plaatsaanduiding van de dia. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Wijzigt de zichtbaarheid van de datum-tijd-plaatsaanduiding van de dia. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Stelt tekst in voor de voettekst-plaatsaanduiding van de layout-dia en alle onderliggende voettekst-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de layout-dia. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Wijzigt de zichtbaarheid van de voettekst-plaatsaanduiding van de layout-dia en alle onderliggende voettekst-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de master-dia. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Stelt tekst in voor de voettekst-plaatsaanduiding van de dia. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Wijzigt de zichtbaarheid van de voettekst-plaatsaanduiding van de dia. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Wijzigt de zichtbaarheid van de paginanummer-plaatsaanduiding van de layout-dia en alle onderliggende paginanummer-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de layout-dia. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Wijzigt de zichtbaarheid van de paginanummer-plaatsaanduiding van de dia. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe pointer-wisselingen in containers naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Krijgt de actuele waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* Naamruimte [Aspose::Slides](../)
* Library [Aspose.Slides](../../)