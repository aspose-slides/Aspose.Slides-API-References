---
title: DefaultBoxedValue
second_title: Aspose.Slides för C++ API-referens
description: "BoxedValue-klassimplementation. Tillåter att BoxingValue-specialiseringar deklareras utan att duplicera gemensam kod. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Packa alltid in denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 274
url: /sv/system/defaultboxedvalue/
---
## DefaultBoxedValue klass

[BoxedValue](../boxedvalue/) klassimplementation. Tillåter att BoxingValue-specialiseringar deklareras utan att duplicera gemensam kod. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assertion-fel. Packa alltid in denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Skapar en ny instans av [DefaultBoxedValue](./) klass som representerar det angivna värdet. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Bestämmer likheten för de inlåsta värdena som representeras av det aktuella och det specificerade objektet. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| int [GetHashCode](./gethashcode/)() const override | Returnerar en hash-kod för det aktuella objektet. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Hämtar den faktiska typen av objektet. |
| **bool** [is](./is/)() const | Bestämmer om typen av det inlåsta värdet som representeras av det aktuella objektet är **V**. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../object/lock/)() | Implementerar låsning enligt C#-statementet lock(). Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjektet. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C#-metoden [Object.MemberwiseClone()](../object/memberwiseclone/). Möjliggör kloning av anpassade typer. |
|  [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värde-typobjekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar den delade referensräknaren med angivet värde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (i stället för delad). Gör det möjligt att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar nuvarande värde för den delade referensräknaren. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar den delade referensräknaren. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Returnerar den strängrepresentation av det inlåsta värdet. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../object/)). |
| const T\& [unbox](./unbox/)() const | Avlåser det inlåsta värdet. |
| void [Unlock](../object/unlock/)() | Implementerar upplåsning enligt C#-statementet lock(). Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar den svaga referensräknaren. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar den svaga referensräknaren. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../object/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)