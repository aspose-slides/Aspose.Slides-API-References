---
title: ITiming
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt animatietiming voor.
type: docs
weight: 443
url: /nl/aspose.slides.animation/itiming/
---
## ITiming klasse

Stelt animatietiming voor.

```cpp
class ITiming : public virtual System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Bootst C#-stijl zwevendekommavergelijking na waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Bootst C#-stijl zwevendekommavergelijking na waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Beschrijft het percentage van de duur van het acceleratiegedragseffect. Leest **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Beschrijft of de animatie automatisch in omgekeerde richting wordt afgespeeld na het afspelen in de vooruitrichting. Leest **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Beschrijft het percentage van de duur van het deceleratiegedragseffect. Leest **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Beschrijft de duur van het animatie-effect. Leest **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Beschrijft het aantal malen dat het effect moet worden herhaald. Leest **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Beschrijft het aantal malen dat het effect moet worden herhaald. Leest **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Dit attribuut geeft aan of het effect zal worden herhaald tot het einde van de dia. Leest **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Dit attribuut geeft aan of het effect zal worden herhaald tot de volgende klik. Leest **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Specificeert of een effect opnieuw moet starten na voltooiing. Leest [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Dit attribuut geeft aan of het effect wordt terugspoeld wanneer het afspelen is voltooid. Leest **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Specificeert het percentage waarmee de timing moet worden versneld (of vertraagd). Leest **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Beschrijft de vertragingstijd na de trigger. Leest **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Beschrijft het type trigger. Leest [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentietellergegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashgeneratie voor aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiecontructor. Kopieert niets, echt, initialiseert gewoon een nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert gewoon een nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr via referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Beschrijft het percentage van de duur van het acceleratiegedragseffect. Schrijft **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Beschrijft of de animatie automatisch in omgekeerde richting wordt afgespeeld na het afspelen in de vooruitrichting. Schrijft **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Beschrijft het percentage van de duur van het deceleratiegedragseffect. Schrijft **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Beschrijft de duur van het animatie-effect. Schrijft **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Beschrijft het aantal malen dat het effect moet worden herhaald. Schrijft **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Beschrijft het aantal malen dat het effect moet worden herhaald. Schrijft **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Dit attribuut geeft aan of het effect zal worden herhaald tot het einde van de dia. Schrijft **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Dit attribuut geeft aan of het effect zal worden herhaald tot de volgende klik. Schrijft **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Specificeert of een effect opnieuw moet starten na voltooiing. Schrijft [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Dit attribuut geeft aan of het effect wordt terugspoeld wanneer het afspelen is voltooid. Schrijft **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Specificeert het percentage waarmee de timing moet worden versneld (of vertraagd). Schrijft **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Beschrijft de vertragingstijd na de trigger. Schrijft **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Beschrijft het type trigger. Schrijft [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th templateargument in op een zwakke pointer (in plaats van gedeeld). Stelt het wisselen van pointers in containers naar zwakke mode mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [Aspose::Slides::Animation](../)
* Bibliotheek [Aspose.Slides](../../)