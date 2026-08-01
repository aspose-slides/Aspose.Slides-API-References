---
title: IEffect
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een animatie-effect.
type: docs
weight: 248
url: /nl/aspose.slides.animation/ieffect/
---
## IEffect klasse

Vertegenwoordigt een animatie-effect.

```cpp
class IEffect : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl floating point vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl floating point vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() | Definieert een kleur na animatie voor het effect. Lees [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() | Definieert een type na animatie voor het effect. Lees [AfterAnimationType](../afteranimationtype/). |
| virtual [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() | Definieert een animatieteksttype voor het effect. De vormtekst kan geanimeerd worden per letter, per woord of in één keer. Lees [AnimateTextType](../animatetexttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) | Retourneert animatiegedrag op de opgegeven index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() | Retourneert verzameling van gedrag voor het effect. Lees [IBehaviorCollection](../ibehaviorcollection/). |
| virtual **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() | Definieert een vertraging tussen geanimeerde tekstdelen (woorden of letters). Een positieve waarde geeft het percentage van de effectduur aan. Een negatieve waarde geeft de vertraging in seconden aan. Lees **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffect](./)\> [get_Effect](./get_effect/)(**int32_t**) | Retourneert een effect van een reeks op de opgegeven index. |
| virtual [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() | Definieert klasse van effect. Lees [EffectPresetClassType](../effectpresetclasstype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() | Retourneert een reeks voor een effect. Alleen-lezen [ISequence](../isequence/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() | Definieert ingesloten geluid voor het effect. Lees [IAudio](../../aspose.slides/iaudio/). |
| virtual **bool** [get_StopPreviousSound](./get_stopprevioussound/)() | Dit attribuut geeft aan of het animatie-effect het vorige geluid stopt. Lees **bool**. |
| virtual [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() | Definieert subtype van effect. Lees [EffectSubtype](../effectsubtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() | Retourneert doelvorm voor het effect. Alleen-lezen [IShape](../../aspose.slides/ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() | Retourneert tekstananimatie. Alleen-lezen [ITextAnimation](../itextanimation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() | Definieert timingwaarde voor het effect. Lees [ITiming](../itiming/). |
| virtual [EffectType](../effecttype/) [get_Type](./get_type/)() | Definieert type van effect. Lees [EffectType](../effecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Stelt het hashen van aangepaste objecten in staat. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analog van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Stelt het klonen van aangepaste types in staat. |
|  [Object](../../system/object/object/)() | Maakt object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en stelt het kopieerconstructoren van subklassen in staat. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en stelt het kopieerconstructoren van subklassen in staat. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) | Definieert een kleur na animatie voor het effect. Schrijf [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) | Definieert een type na animatie voor het effect. Schrijf [AfterAnimationType](../afteranimationtype/). |
| virtual void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) | Definieert een animatieteksttype voor het effect. De vormtekst kan geanimeerd worden per letter, per woord of in één keer. Schrijf [AnimateTextType](../animatetexttype/). |
| virtual void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) | Stelt animatiegedrag in op de opgegeven index. |
| virtual void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) | Retourneert verzameling van gedrag voor het effect. Schrijf [IBehaviorCollection](../ibehaviorcollection/). |
| virtual void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) | Definieert een vertraging tussen geanimeerde tekstdelen (woorden of letters). Een positieve waarde geeft het percentage van de effectduur aan. Een negatieve waarde geeft de vertraging in seconden aan. Schrijf **float**. |
| virtual void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) | Definieert klasse van effect. Schrijf [EffectPresetClassType](../effectpresetclasstype/). |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) | Definieert ingesloten geluid voor het effect. Schrijf [IAudio](../../aspose.slides/iaudio/). |
| virtual void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) | Dit attribuut geeft aan of het animatie-effect het vorige geluid stopt. Schrijf **bool**. |
| virtual void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) | Definieert subtype van effect. Schrijf [EffectSubtype](../effectsubtype/). |
| virtual void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | Definieert timingwaarde voor het effect. Schrijf [ITiming](../itiming/). |
| virtual void [set_Type](./set_type/)([EffectType](../effecttype/)) | Definieert type van effect. Schrijf [EffectType](../effecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/) methode. Stelt het converteren van aangepaste objecten naar string in staat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [Aspose::Slides::Animation](../)
* Bibliotheek [Aspose.Slides](../../)