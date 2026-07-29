---
title: IEquatable
second_title: Aspose.Slides för C++ API-referens
description: "Definierar en metod som bestämmer likheten mellan två objekt. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 976
url: /sv/system/iequatable/
---
## IEquatable klass

Definierar en metod som bestämmer likheten mellan två objekt. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class IEquatable : public virtual System::Object
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of the compared objects |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](./equals/)(T) | Bestämmer om det aktuella och det angivna objektet är lika. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../object/gettype/)-anrop. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../object/lock/)() | Implementerar C#-lock()-satsens låsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräknare med det angivna värdet. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog till C# [Object.ToString()](../object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktion. |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../object/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)