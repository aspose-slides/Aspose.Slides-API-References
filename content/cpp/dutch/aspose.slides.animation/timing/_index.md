---
title: Timing
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt animatietiming.
type: docs
weight: 625
url: /nl/aspose.slides.animation/timing/
---
## Timingklasse

Representeert animatietiming.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| **float** [get_Accelerate](./get_accelerate/)() override | Beschrijft het percentage van de duurversnellingsgedragseffect. Lees **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Beschrijft of de animatie automatisch in omgekeerde richting wordt afgespeeld nadat deze in de voorwaartse richting is afgespeeld. Lees **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Beschrijft het percentage van de duurvertragingengedragseffect. Lees **float**. |
| **float** [get_Duration](./get_duration/)() override | Beschrijft de duur van het animatie-effect. Lees **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Beschrijft het aantal keren dat het effect moet herhalen. Lees **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Beschrijft het aantal keren dat het effect moet herhalen. Lees **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Dit attribuut geeft aan of het effect herhaalt tot het einde van de dia. Lees **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Dit attribuut geeft aan of het effect herhaalt tot de volgende klik. Lees **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Specificeert of een effect opnieuw moet starten na voltooiing. Lees [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Dit attribuut geeft aan of het effect wordt teruggespoeld wanneer het afspelen is voltooid. Lees **bool**. |
| **float** [get_Speed](./get_speed/)() override | Specificeert het percentage waarmee de timing wordt versneld (of vertraagd). Lees **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Beschrijft de vertragingstijd na de trigger. Lees **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Beschrijft het type trigger. Lees [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement locking. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Beschrijft het percentage van de duurversnellingsgedragseffect. Schrijf **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Beschrijft of de animatie automatisch in omgekeerde richting wordt afgespeeld nadat deze in de voorwaartse richting is afgespeeld. Schrijf **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Beschrijft het percentage van de duurvertragingengedragseffect. Schrijf **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Beschrijft de duur van het animatie-effect. Schrijf **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Beschrijft het aantal keren dat het effect moet herhalen. Schrijf **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Beschrijft het aantal keren dat het effect moet herhalen. Schrijf **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Dit attribuut geeft aan of het effect herhaalt tot het einde van de dia. Schrijf **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Dit attribuut geeft aan of het effect herhaalt tot de volgende klik. Schrijf **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Specificeert of een effect opnieuw moet starten na voltooiing. Schrijf [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Dit attribuut geeft aan of het effect wordt teruggespoeld wanneer het afspelen is voltooid. Schrijf **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Specificeert het percentage waarmee de timing wordt versneld (of vertraagd). Schrijf **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Beschrijft de vertragingstijd na de trigger. Schrijf **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Beschrijft het type trigger. Schrijf [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ITiming](../itiming/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Naamruimte [Aspose::Slides::Animation](../)
* Bibliotheek [Aspose.Slides](../../)