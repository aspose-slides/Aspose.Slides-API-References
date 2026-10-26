---
title: BoxedValue
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett inkapslat värde. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertionfel. Inslut alltid denna klass i en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 105
url: /sv/system/boxedvalue/
---
## BoxedValue klass

Representerar ett inkapslat värde. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller assertion-fel. Inslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av det inkapslade värdet som representeras av klassen |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BoxedValue](./boxedvalue/)(const T\&) | Skapar ett objekt som representerar det angivna värdet inkapslat. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Bestämmer likheten för de inkapslade värdena som representeras av det aktuella och det angivna objektet. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika trots att enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika trots att enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| int [GetHashCode](./gethashcode/)() const override | Returnerar en hashkod för det aktuella objektet. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Hämtar den faktiska typen för objektet. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | Returnerar värdet som representerar typen för det inkapslade värdet som representeras av det aktuella objektet. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Returnerar det numeriska värdet för det inkapslade objektet om det kan castas, annars noll. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| **bool** [is](./is/)() const | Bestämmer om typen för det inkapslade värdet som representeras av det aktuella objektet är **V**. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Bestämmer om det aktuella objektet representerar ett inkapslat värde av enum-typ. |
| void [Lock](../object/lock/)() | Implementerar C# lock()-satset för låsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
| [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Inkapslar värdet för en enumerationskonstant i den angivna uppräkningen med det angivna namnet. En parameter anger om skiftläget ska ignoreras vid tolkning av strängen som specificerar namnet på enumerationskonstanten. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Inkapslar värdet för en enumerationskonstant i den angivna uppräkningen med det angivna namnet. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter det n:e mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde för den delade referensräknaren. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar den delade referensräknaren. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Konverterar det inkapslade värdet som representeras av det aktuella objektet till en sträng. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Konverterar det inkapslade objektet till en sträng med angiven formatsträng. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktionen. |
| const T\& [unbox](./unbox/)() const | Avkapslar värdet som representeras av det aktuella objektet. |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-satset för upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar den svaga referensräknaren. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar den svaga referensräknaren. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [~Object](../object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [BoxedValueBase](../boxedvaluebase/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)