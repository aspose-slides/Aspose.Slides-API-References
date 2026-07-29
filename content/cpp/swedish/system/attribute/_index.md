---
title: Attribute
second_title: Aspose.Slides för C++ API-referens
description: "En bas-klass för anpassade attribut. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assert-fel. Inneslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 53
url: /sv/system/attribute/
---
## Attribut klass


En bas-klass för anpassade attribut. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assert-fel. Inneslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Attribute : public System::Object
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med hjälp av C# [Object.Equals](../object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| static [Object::ptr](../object/ptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](../typeinfo/)\&, const [TypeInfo](../typeinfo/)\&) | Returnerar ett anpassat attribut av en angiven typ som tillämpas på den angivna typen. |
| static [ArrayPtr](../arrayptr/)\<[Object::ptr](../object/ptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](../typeinfo/)\&) | Returnerar alla anpassade attribut som tillämpas på den angivna typen. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../object/gettype/) anrop. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/) metod. Möjliggör kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, den initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, den initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätt n'th mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog till C# [Object.ToString()](../object/tostring/) metod. Möjliggör konvertering av anpassade objekt till string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/)) konstruktion. |
| void [Unlock](../object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [Object](../object/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)