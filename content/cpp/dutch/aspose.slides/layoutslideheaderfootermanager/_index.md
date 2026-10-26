---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een manager voor die het gedrag van de indelingsdia-voettekst, datum-tijd- en paginanummer-plaatsaanduidingen en alle onderliggende plaatsaanduidingen bevat. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de indelingsdia.
type: docs
weight: 4317
url: /nl/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager klasse


Stelt een manager voor die het gedrag van de indelingsdia-voettekst, datum-tijd- en paginanummer-plaatsaanduidingen en alle onderliggende plaatsaanduidingen bevat. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de indelingsdia.

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan een waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan een waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Haalt waarde op die aangeeft dat een datum-tijd-plaatsaanduiding aanwezig is. Leest**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Haalt waarde op die aangeeft dat een voettekst-plaatsaanduiding aanwezig is. Leest **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Haalt waarde op die aangeeft dat een paginanummer-plaatsaanduiding aanwezig is. Leest**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Stelt het hashen van aangepaste objecten toe. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Stelt het klonen van aangepaste types toe. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie van waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Stelt tekst in voor de indelingsdia-datum-tijd-plaatsaanduiding en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de indelingsdia. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Wijzigt de zichtbaarheid van de indelingsdia-datum-tijd-plaatsaanduiding en alle onderliggende datum-tijd-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de indelingsdia. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Stelt tekst in voor de dia-datum-tijd-plaatsaanduiding. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Wijzigt de zichtbaarheid van de dia-datum-tijd-plaatsaanduiding. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Stelt tekst in voor de indelingsdia-voettekst-plaatsaanduiding en alle onderliggende voettekst-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de indelingsdia. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Wijzigt de zichtbaarheid van de indelingsdia-voettekst-plaatsaanduiding en alle onderliggende voettekst-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de masterdia. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Stelt tekst in voor de dia-voettekst-plaatsaanduiding. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Wijzigt de zichtbaarheid van de dia-voettekst-plaatsaanduiding. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Wijzigt de zichtbaarheid van de indelingsdia-paginanummer-plaatsaanduiding en alle onderliggende paginanummer-plaatsaanduidingen. Onderliggende plaatsaanduidingen betekenen dat de plaatsaanduidingen zich bevinden op afhankelijke dia's. Afhankelijke dia's gebruiken en hangen af van de indelingsdia. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Wijzigt de zichtbaarheid van de dia-paginanummer-plaatsaanduiding. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Stelt het omzetten van aangepaste objecten naar string toe. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* Klasse [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)