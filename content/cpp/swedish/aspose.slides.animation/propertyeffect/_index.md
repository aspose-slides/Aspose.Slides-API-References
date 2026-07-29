---
title: PropertyEffect
second_title: Aspose.Slides för C++ API-referens
description: Representerar egenskapseffektbeteende.
type: docs
weight: 521
url: /sv/aspose.slides.animation/propertyeffect/
---
## PropertyEffect klass

Representerar egenskapseffektbeteende.

```cpp
class PropertyEffect : public Aspose::Slides::Animation::Behavior,
                       public Aspose::Slides::Animation::IPropertyEffect
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna syften. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | Anger om animationsbeteenden ackumuleras. Läs [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | Anger om det aktuella animationsbeteendet kombineras med andra pågående animationer. Läs [BehaviorAdditiveType](../behavioradditivetype/). |
| [System::String](../../system/string/) [get_By](./get_by/)() override | Anger ett relativt förskjutningsvärde för animationen i förhållande till dess position före animationens start. Läs [System::String](../../system/string/). |
| [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() override | Anger interpolationsläge för animationen. Läs [PropertyCalcModeType](../propertycalcmodetype/). |
| [System::String](../../system/string/) [get_From](./get_from/)() override | Anger startvärdet för animationen. Läs [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) override | Returnerar en punkt i animationen på det angivna indexet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() override | Anger animationens punkter. Läs [IPointCollection](../ipointcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | Representerar egenskaper för beteendet. Skrivskyddad [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | Representerar tidsegenskaper för effektbeteendet. Läs [ITiming](../itiming/). |
| [System::String](../../system/string/) [get_To](./get_to/)() override | Anger slutvärdet för animationen. Läs [System::String](../../system/string/). |
| [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() override | Anger typen av ett egenskapsvärde. Läs [PropertyValueType](../propertyvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
|  [PropertyEffect](./propertyeffect/)() |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | Anger om animationsbeteenden ackumuleras. Skriv [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | Anger om det aktuella animationsbeteendet kombineras med andra pågående animationer. Skriv [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_By](./set_by/)([System::String](../../system/string/)) override | Anger ett relativt förskjutningsvärde för animationen i förhållande till dess position före animationens start. Skriv [System::String](../../system/string/). |
| void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) override | Anger interpolationsläge för animationen. Skriv [PropertyCalcModeType](../propertycalcmodetype/). |
| void [set_From](./set_from/)([System::String](../../system/string/)) override | Anger startvärdet för animationen. Skriv [System::String](../../system/string/). |
| void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) override | Anger animationens punkter. Skriv [IPointCollection](../ipointcollection/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Representerar tidsegenskaper för effektbeteendet. Skriv [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::String](../../system/string/)) override | Anger slutvärdet för animationen. Skriv [System::String](../../system/string/). |
| void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) override | Anger typen av ett egenskapsvärde. Skriv [PropertyValueType](../propertyvaluetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Möjliggör att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [Behavior](../behavior/)
* Klass [IPropertyEffect](../ipropertyeffect/)
* Namnrymd [Aspose::Slides::Animation](../)
* Bibliotek [Aspose.Slides](../../)