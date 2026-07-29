---
title: Effect
second_title: Aspose.Slides för C++ API-referens
description: Representerar en animationseffekt.
type: docs
weight: 118
url: /sv/aspose.slides.animation/effect/
---
## Effektklass

Representerar en animationseffekt.

```cpp
class Effect : public Aspose::Slides::Animation::IEffect,
               public Aspose::Slides::IDOMObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med någon värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med någon värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() override | Definierar en efter-animation-färg för effekt. Läs [IColorFormat](../../aspose.slides/icolorformat/). |
| [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() override | Definierar en efter-animation-typ för effekt. Läs [AfterAnimationType](../afteranimationtype/). |
| [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() override | Definierar en animerad text-typ för effekt. Formens text kan animeras per bokstav, per ord eller hela på en gång. Läs [AnimateTextType](../animatetexttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) override | Returnerar animationsbeteende på det angivna indexet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() override | Returnerar en samling av beteenden för effekt. Läs [IBehaviorCollection](../ibehaviorcollection/). |
| **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() override | Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procent av effektens varaktighet. Ett negativt värde anger fördröjning i sekunder. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [get_Effect](./get_effect/)(**int32_t**) override | Returnerar en påverkan av en sekvens på det angivna indexet. |
| [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() override | Definierar klass av effekt. Läs [EffectPresetClassType](../effectpresetclasstype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() override | Returnerar en sekvens för en effekt. Endast läsning [ISequence](../isequence/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Definierade inbäddat ljud för effekt. Läs [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_StopPreviousSound](./get_stopprevioussound/)() override | Detta attribut anger om animationseffekten stoppar det föregående ljudet. Läs **bool**. |
| [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() override | Definierar undertyp av effekt. Läs [EffectSubtype](../effectsubtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() override | Returnerar målform för effekt. Endast läsning [IShape](../../aspose.slides/ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() override | [TextAnimation](../textanimation/) Endast läsning [ITextAnimation](../itextanimation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() override | Definierar tidsvärde för effekt. Läs [ITiming](../itiming/). |
| [EffectType](../effecttype/) [get_Type](./get_type/)() override | Definierar typ av effekt. Läs [EffectType](../effecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenskontostruktur associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objekt. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-väktarobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | Definierar en efter-animation-färg för effekt. Skriv [IColorFormat](../../aspose.slides/icolorformat/). |
| void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) override | Definierar en efter-animation-typ för effekt. Skriv [AfterAnimationType](../afteranimationtype/). |
| void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) override | Definierar en animerad text-typ för effekt. Formens text kan animeras per bokstav, per ord eller hela på en gång. Skriv [AnimateTextType](../animatetexttype/). |
| void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) override | Ställer in animationsbeteende på det angivna indexet. |
| void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) override | Returnerar en samling av beteenden för effekt. Skriv [IBehaviorCollection](../ibehaviorcollection/). |
| void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) override | Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procent av effektens varaktighet. Ett negativt värde anger fördröjning i sekunder. Skriv **float**. |
| void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) override | Definierar klass av effekt. Skriv [EffectPresetClassType](../effectpresetclasstype/). |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Definierade inbäddat ljud för effekt. Skriv [IAudio](../../aspose.slides/iaudio/). |
| void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) override | Detta attribut anger om animationseffekten stoppar det föregående ljudet. Skriv **bool**. |
| void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) override | Definierar undertyp av effekt. Skriv [EffectSubtype](../effectsubtype/). |
| void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Definierar tidsvärde för effekt. Skriv [ITiming](../itiming/). |
| void [set_Type](./set_type/)([EffectType](../effecttype/)) override | Definierar typ av effekt. Skriv [EffectType](../effecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te template-argument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-väktarobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IEffect](../ieffect/)
* Klass [IDOMObject](../../aspose.slides/idomobject/)
* Namnrymd [Aspose::Slides::Animation](../)
* Bibliotek [Aspose.Slides](../../)