---
title: DecoderExceptionFallback
second_title: Aspose.Slides voor C++ API-referentie
description: "Biedt een fallback-strategie die uitzonderingen gooit. Objecten van deze klasse mogen alleen worden gealloceerd met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 27
url: /nl/system.text/decoderexceptionfallback/
---
## DecoderExceptionFallback klasse

Biedt een fallbackstrategie die uitzonderingen gooit. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten tot gevolg heeft. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class DecoderExceptionFallback : public System::Text::DecoderFallback
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [DecoderFallbackBufferPtr](../../system/decoderfallbackbufferptr/) [CreateFallbackBuffer](./createfallbackbuffer/)() override | Creëert een fallback-buffer. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static const [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_ExceptionFallback](../decoderfallback/get_exceptionfallback/)() | Haalt de standaard exception fallback-implementatie op. |
| int [get_MaxCharCount](./get_maxcharcount/)() const override | Haalt het maximale aantal tekens op dat de instantie kan retourneren. |
| static const [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_ReplacementFallback](../decoderfallback/get_replacementfallback/)() | Haalt de standaard vervangende fallback-implementatie op. |
| static const [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_StandardSafeFallback](../decoderfallback/get_standardsafefallback/)() | Haalt de standaard veilige fallback-implementatie op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt het hashen van aangepaste objecten in staat. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, echt; initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt; initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [DecoderFallback](../decoderfallback/)
* Naamruimte [System::Text](../)
* Bibliotheek [Aspose.Slides](../../)