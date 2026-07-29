---
title: BoxedEnum
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett inkapslat uppräkningsvärde. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 92
url: /sv/system/boxedenum/
---
## BoxedEnum klass


Representerar ett inkapslat uppräkningsvärde. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller assertionsfel. Omge alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename E,typename UT>class BoxedEnum : public System::BoxedValue<typename std::underlying_type<E>::type>
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| E | Typ av uppräkningsvärde |
| UT | Den underliggande typen för uppräkning **E** |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [BoxedEnum](./boxedenum/)(E) | Skapar en instans som representerar det angivna uppräkningsvärdet. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../object/gettype/)-anrop. |
| virtual [TypeCode](../typecode/) [GetTypeCode](../boxedvaluebase/gettypecode/)() const | Returnerar värdet som representerar typen av det inkapslade värdet som representeras av det aktuella objektet. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Konverterar värdet av den inkapslade uppräkningskonstanten till ett 64-bits heltal. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Bestämmer om det aktuella objektet representerar ett inkapslat värde av enum-typ. |
| void [Lock](../object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Inkapslar värdet av uppräkningskonstanten för den angivna uppräkningen med det angivna namnet. En parameter anger om skiftläget ska ignoreras vid tolkning av strängen som specificerar namnet på uppräkningskonstanten. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Inkapslar värdet av uppräkningskonstanten för den angivna uppräkningen med det angivna namnet. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar det delade referensräknet med angivet värde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar nuvarande värde för delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [System::String](../string/) [ToString](./tostring/)() const override | Konverterar det inkapslade värdet som representeras av det aktuella objektet till en sträng. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Konverterar inkapslat objekt till sträng med angiven formatsträng. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktion. |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [BoxedValue](../boxedvalue/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)