---
title: Object
second_title: Aspose.Slides för C++ API-referens
description: Basklass som möjliggör användning av metoder som är tillgängliga för System.Object-klassen i C#. Alla icke-triviala klasser som används i den översatta miljön bör ärva den.
type: docs
weight: 1132
url: /sv/system/object/
---
## Objektklass

Base class that enables using methods available for [System.Object](./) class in C#. All non-trivial classes used with translated environment should inherit it.

```cpp
class Object
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Jämför objekt med C# [Object.Equals](./equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analog till C# [Object.GetHashCode()](./gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](./gettype/)-anrop. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](./lock/)() | Implementerar låsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](./memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](./object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](./object/)([Object](./) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](./referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](./referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Sätter det n-te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](./sharedcount/)() const | Hämtar nuvarande värde av delad referensräknare. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analog till C# [Object.ToString()](./tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implementerar C# typeof([System.Object](./))-konstruktion. |
| void [Unlock](./unlock/)() | Implementerar låsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](./weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](./~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [ptr](./ptr/) | Alias för smart pekartyper. |

## Anmärkningar

Förutom metoderna som finns i C# [System.Object](./)-klassen möjliggör den även stöd för vissa koncept specifika för den översatta kodmiljön. Detta inkluderar referensräkning som används av smartpekarklasser ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) och andra tjänster relaterade till minneshantering, felsökning med mera.

Varje [Object](./) har två referensräknare: delad referensräknare och svag referensräknare. Den svaga referensräknaren lagras alltid i en fristående datastruktur snarare än i [Object](./) självt, vilket möjliggör att svaga pekare överlever det refererade objektet. Den smarta referensräknaren lagras antingen i objektet självt eller i samma fristående struktur, beroende på macro-tillståndet ENABLE_EXTERNAL_REFCOUNT. Som standard är den aktiverad i debug-byggen och inaktiverad i release-byggen. Om smart pekarräknaren lagras i objektet självt skapas den fristående datastrukturen endast om svaga pekare till objektet finns. Annars skapas den tillsammans med objektet självt.

Alla smarta pekare använder dessa två referensräknare och bidrar till samma och enda ägarskapsgrupp.

Om en [Object](./)-subklass skapas på stacken får inga smarta pekare till den skapas, annars uppstår ett problem med stack-borttagning.

Denna typ kan allokeras antingen på stacken som värdetyp eller i heapen med [System::MakeObject()](../makeobject/)-funktionen. När objektet har allokerats får man aldrig blanda dessa två användningsfall: att ha [SmartPtr](../smartptr/)-pekare på stack-allokerade objekt är strikt förbjudet.

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)