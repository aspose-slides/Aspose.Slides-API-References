---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een manager voor die het gedrag van alle voettekst-, datum-tijd- en paginanummer-plaatsaanduidingen van de presentatie bevat.
type: docs
weight: 4863
url: /nl/aspose.slides/presentationheaderfootermanager/
---
## PresentationHeaderFooterManager klasse

Stelt een manager voor die het gedrag van alle voettekst-, datum-tijd- en paginanummer-plaatsaanduidingen van de presentatie bevat.

```cpp
class PresentationHeaderFooterManager : public Aspose::Slides::BaseHeaderFooterManager,
                                        public Aspose::Slides::IPresentationHeaderFooterManager
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het door targetType beschreven type vertegenwoordigt. Analog van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock()-instructie. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waakhondobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieer-constructor. Kopieert niets, initialiseert slechts een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert slechts een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waarde-type-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) override | Stelt de tekst in voor alle datum-tijd-plaatsaanduidingen, inclusief masterslides, lay-out-slides, slides, notitie-master, notitie-slides en handout-master. |
| void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) override | Wijzigt de zichtbaarheid van alle datum-tijd-plaatsaanduidingen, inclusief masterslides, lay-out-slides, slides, notitie-master, notitie-slides en handout-master. |
| void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) override | Stelt de tekst in voor alle voettekst-plaatsaanduidingen, inclusief masterslides, lay-out-slides, slides, notitie-master, notitie-slides en handout-master. |
| void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) override | Wijzigt de zichtbaarheid van alle voettekst-plaatsaanduidingen, inclusief masterslides, lay-out-slides, slides, notitie-master, notitie-slides en handout-master. |
| void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) override | Stelt de tekst in voor alle kop-plaatsaanduidingen, inclusief notitie-master, notitie-slides en handout-master. |
| void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) override | Wijzigt de zichtbaarheid van alle kop-plaatsaanduidingen, inclusief notitie-master, notitie-slides en handout-master. |
| void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) override | Wijzigt de zichtbaarheid van alle paginanummer-plaatsaanduidingen, inclusief masterslides, lay-out-slides, slides, notitie-master, notitie-slides en handout-master. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) override | Wijzigt de zichtbaarheid van de voettekst-, datum-tijd- en paginanummer-plaatsaanduidingen voor alle titelslides en voor de eerste lay-out-slide. Titelslides \u2013 slides gebaseerd op de eerste lay-out-slide (ongeacht het type van deze eerste lay-out). |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Vermindert en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-instructie. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waakhondobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Vermindert de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [BaseHeaderFooterManager](../baseheaderfootermanager/)
* Klasse [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)