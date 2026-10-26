---
title: ITiming
second_title: Aspose.Slides för C++ API-referens
description: Representerar animationstiming.
type: docs
weight: 443
url: /sv/aspose.slides.animation/itiming/
---
## ITiming klass

Representerar animationstiming.

```cpp
class ITiming : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Beskriver procentsatsen av varaktigheten för accelerationsbeteendeeffekten. Läs **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Beskriver huruvida animationen automatiskt ska spelas upp i omvänd riktning efter att ha spelats framåt. Läs **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Beskriver procentsatsen av varaktigheten för decelerationsbeteendeeffekten. Läs **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Beskriver varaktigheten av animationseffekten. Läs **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Beskriver antalet gånger effekten ska upprepas. Läs **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Beskriver antalet gånger effekten ska upprepas. Läs **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Detta attribut specificerar om effekten ska upprepas till slutet av bilden. Läs **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Detta attribut specificerar om effekten ska upprepas till nästa klick. Läs **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Specificerar om en effekt ska startas om efter fullbordning. Läs [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Detta attribut specificerar om effekten ska spolas tillbaka när den är klar. Läs **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Specificerar procentsatsen för att påskynda (eller sakta ner) timingen. Läs **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Beskriver fördröjningstid efter utlösare. Läs **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Beskriver utlösartyp. Läs [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Beskriver procentsatsen av varaktigheten för accelerationsbeteendeeffekten. Skriv **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Beskriver huruvida animationen automatiskt ska spelas upp i omvänd riktning efter att ha spelats framåt. Skriv **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Beskriver procentsatsen av varaktigheten för decelerationsbeteendeeffekten. Skriv **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Beskriver varaktigheten av animationseffekten. Skriv **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Beskriver antalet gånger effekten ska upprepas. Skriv **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Beskriver antalet gånger effekten ska upprepas. Skriv **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Detta attribut specificerar om effekten ska upprepas till slutet av bilden. Skriv **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Detta attribut specificerar om effekten ska upprepas till nästa klick. Skriv **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Specificerar om en effekt ska startas om efter fullbordning. Skriv [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Detta attribut specificerar om effekten ska spolas tillbaka när den är klar. Skriv **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Specificerar procentsatsen för att påskynda (eller sakta ner) timingen. Skriv **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Beskriver fördröjningstid efter utlösare. Skriv **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Beskriver utlösartyp. Skriv [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låssläpp enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides::Animation](../)
* Bibliotek [Aspose.Slides](../../)