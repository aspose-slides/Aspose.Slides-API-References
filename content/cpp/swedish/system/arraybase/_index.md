---
title: ArrayBase
second_title: Aspose.Slides för C++ API-referens
description: Dummy för System.Array-klass (abstrakt basklass för alla arrayer) kan fyllas med funktionalitet på begäran.
type: docs
weight: 27
url: /sv/system/arraybase/
---
## ArrayBase klass

Den dummy för [System.Array](../array/) klass (abstrakt basklass för alla arrayer) kan fyllas med funktionalitet på begäran.

```cpp
class ArrayBase : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual **int32_t** [get_Length](./get_length/)() const | Returnerar ett 32-bitars heltal som representerar det totala antalet element i alla dimensioner av arrayen. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar det faktiska typ av objektet. Analog till C# [System.Object.GetType()](../object/gettype/)-anropet. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vakterobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| virtual void * [raw_data_ptr](./raw_data_ptr/)() | Returnerar pekare till det första elementet i en endimensionell array. För fler-dimensionella arrayer är resultatet odefinierat. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument till en svag pekare (istället för delad). Möjliggör att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde för den delade referensräknaren. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar den delade referensräknaren. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog till C# [Object.ToString()](../object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktion. |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vakterobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se också

* Klass [Object](../object/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)