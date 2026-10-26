---
title: ObjectExt
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller statiska metoder som efterliknar C# Object-metoder som anropas för icke-Object C++-typer (strängar, tal osv.). Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 1145
url: /sv/system/objectext/
---
## ObjectExt class


Tillhandahåller statiska metoder som efterliknar C# [Object](../object/)-metoder som anropas för icke-Object C++-typer (strängar, tal osv.). Detta är en statisk typ utan instans-tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class ObjectExt : public System::ObjectType
```

## Methods

| Metod | Beskrivning |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Konverterar grundläggande array-värden (vilket C# gör implicit men C++ tydligen inte). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Packar värdetyper för konvertering till [Object](../object/). Implementering för enum-typer. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Packar värdetyper för konvertering till [Object](../object/). Implementering för icke-enum-typer. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Packar [Nullable](../nullable/)-typer för konvertering till [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Packar strängvärden. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Packar enum-typer för att spridas som [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementering av översättning av '??'-operatorn för icke-nullbara typer. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementering av översättning av '??'-operatorn för nullbara typer. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementering av översättning av '??='-operatorn. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementering av översättning av '??'-operatorn för icke-nullbara typer. Överlagring för fallet då RT2 kan konverteras till RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Ersättning för C# [Object.Equals](../object/equals/)-anrop som fungerar för alla typer i C++. Överlagring för smarta pekartyper. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Ersättning för C# [Object.Equals](../object/equals/)-anrop som fungerar för alla typer i C++. Överlagring för strukturtyper. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Ersättning för C# [Object.Equals](../object/equals/)-anrop som fungerar för alla typer i C++. Överlagring för skalära typer. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Ersättning för C# [Object.Equals](../object/equals/)-anrop som fungerar för alla typer i C++. Överlagring för strängliteral med strängjämförelse. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Efterliknar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika, även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Efterliknar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika, även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implementerar [GetHashCode()](./gethashcode/)-anrop; fungerar på både [Object](../object/)-subklasser och orelaterade typer. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementerar typeof()-översättning. Överlagring för smarta pekare. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementerar typeof()-översättning. Överlagring för strukturer. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementerar typeof()-översättning. Överlagring för undantag. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementerar typeof()-översättning. Överlagring för primitiva typer. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementerar typeof()-översättning. Överlagring för [Nullable](../nullable/)-typer. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för primitiva typer. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för enum-typer. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för strukturer och pekare. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för strukturer och pekare. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implementerar typeof()-översättning. Överlagring för strängtyp. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementerar typeof()-översättning. Överlagring för **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implementerar 'is'-operatorns översättning. Specialisering för boxable (value)-typer som exakt är de. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementerar 'is'-operatorns översättning. Specialisering för pekartyper optimerade för 'final'-klasser. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementerar 'is'-operatorns översättning. Specialisering för pekartyper. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementerar 'is'-operatorns översättning. Specialisering för värdetyper. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementerar 'is'-operatorns översättning. Specialisering för icke-konverterbara typer. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för pekartyper. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för undantags-wrapper-typer. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för nullable-typer. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för boxable-typer med definierad ==-operator. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för boxable-typer utan definierad ==-operator. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för värdetyper som är boxade till gränssnitt. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för enum-typer. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för enum-typer mot svaga pekare. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implementerar 'is'-operatorns översättning. Specialisering för [Nullable](../nullable/)-typ. |
| static **bool** [Is](./is/)(const char16_t *) | Implementerar 'is'-operatorns översättning. Specialisering för strängliteral. |
| static **bool** [Is](./is/)(**int32_t**) | Implementerar 'is'-operatorns översättning. Specialisering för heltalsliteral. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Kontrollerar om objektet är ett boxat värde. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Konverterar [Object](../object/) till okänd typ, hanterar både smart pekartyp och bpxed-värdesituationer. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Konverterar [Object](../object/) till okänd typ, hanterar både smart pekartyp och boxade värdesituationer. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Ersättning för C# ToString-metod för att fungera på alla C++-typer. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Avboxar värdetyper efter konvertering till [Object](../object/). Implementering för enum-typer. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Avboxar värdetyper efter konvertering till [Object](../object/). Implementering för icke-enum- och icke-nullbara typer. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Avboxar värdetyper efter konvertering till [Object](../object/). Implementering för icke-enum- och icke-nullbara typer. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Avboxar enum-typer till heltal. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Konverterar enum-typer. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Avboxar strängvärden. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Avboxar sträng från boxat värde. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Avboxar objekt till nullable-typ. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Kontrollerar om ett objekt av okänd typ är nullptr. Överlagring för icke-skalära typer. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Kontrollerar om ett objekt av okänd typ är nullptr. Överlagring för skalära typer. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Konverterar okänd typ till [Object](../object/), hanterar både smart pekartyp och värdetypssituationer. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Konverterar okänd typ till [Object](../object/), hanterar både smart pekartyp och värdetypssituationer. |

## See Also

* Klass [ObjectType](../objecttype/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)