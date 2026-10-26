---
title: ObjectExt
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt statische methoden die C# Object-methoden emuleren die worden aangeroepen voor niet-Object C++-typen (strings, getallen, enz.). Dit is een statisch type zonder instantie-services. Je mag nooit exemplaren ervan maken op welke manier dan ook.
type: docs
weight: 1145
url: /nl/system/objectext/
---
## ObjectExt klasse


Biedt statische methoden die C# [Object](../object/)-methoden emuleren die worden aangeroepen voor niet-Object C++-typen (strings, getallen, enz.). Dit is een statisch type zonder instantie-services. Je mag nooit exemplaren ervan maken op welke manier dan ook.

```cpp
class ObjectExt : public System::ObjectType
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Converteert array-fundamentele waarden (die C# impliciet doet, maar C++ blijkbaar niet). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boxt waardetypen voor conversie naar [Object](../object/). Implementatie voor enum-typen. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boxt waardetypen voor conversie naar [Object](../object/). Implementatie voor niet-enum-typen. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boxt [Nullable](../nullable/)-typen voor conversie naar [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Boxt string-waarden. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Boxt enum-typen voor propagatie als [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementatie van de '??'-operatorvertaling voor niet-null-typen. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementatie van de '??'-operatorvertaling voor nullable-typen. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementatie van de '??='-operatorvertaling. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementatie van de '??'-operatorvertaling voor niet-null-typen. Overload voor het geval dat RT2 converteerbaar is naar RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Vervanging voor C# [Object.Equals](../object/equals/)-aanroepen die voor elk type in C++ werken. Overload voor smart-pointer-typen. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Vervanging voor C# [Object.Equals](../object/equals/)-aanroepen die voor elk type in C++ werken. Overload voor struct-typen. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Vervanging voor C# [Object.Equals](../object/equals/)-aanroepen die voor elk type in C++ werken. Overload voor scalar-typen. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Vervanging voor C# [Object.Equals](../object/equals/)-aanroepen die voor elk type in C++ werken. Overload voor string-literal met stringvergelijking. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implementeert [GetHashCode()](./gethashcode/)-aanroepen; werkt zowel op [Object](../object/)-subklassen als op niet-gerelateerde typen. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementeert typeof()-vertaling. Overload voor smart-pointers. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementeert typeof()-vertaling. Overload voor structuren. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementeert typeof()-vertaling. Overload voor uitzonderingen. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementeert typeof()-vertaling. Overload voor primitieve typen. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementeert typeof()-vertaling. Overload voor [Nullable](../nullable/)-typen. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor primitieve typen. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor enum-typen. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor structuren en pointers. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor structuren en pointers. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implementeert typeof()-vertaling. Overload voor stringtype. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementeert typeof()-vertaling. Overload voor **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor boxbare (waarde)-typen, wat precies betekent dat ze dat zijn. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor pointer-typen geoptimaliseerd voor 'final'-klassen. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor pointer-typen. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor waarde-typen. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor niet-converteerbare typen. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor pointer-typen. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor uitzondering-wrapper-typen. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor nullable-typen. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor boxbare typen met ==-operator gedefinieerd. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor boxbare typen zonder gedefinieerde ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor waardetypen die naar interfaces zijn geboxd. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor enum-typen. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor enum-typen versus zwakke pointers. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implementeert 'is'-operatorvertaling. Specialisatie voor [Nullable](../nullable/)-type. |
| static **bool** [Is](./is/)(const char16_t *) | Implementeert 'is'-operatorvertaling. Specialisatie voor string-literal. |
| static **bool** [Is](./is/)(**int32_t**) | Implementeert 'is'-operatorvertaling. Specialisatie voor integer-literal. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Controleert of object een geboxte waarde is. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Converteert [Object](../object/) naar onbekend type, waarbij zowel smart-pointer-type als geboxte waardesituaties worden afgehandeld. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Converteert [Object](../object/) naar onbekend type, waarbij zowel smart-pointer-type als geboxte waardesituaties worden afgehandeld. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Vervanging voor de C# ToString-methode om op elk C++-type te werken. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deboxt waardetypen na conversie naar [Object](../object/). Implementatie voor enum-typen. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deboxt waardetypen na conversie naar [Object](../object/). Implementatie voor niet-enum- en niet-null-typen. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deboxt waardetypen na conversie naar [Object](../object/). Implementatie voor niet-enum- en niet-null-typen. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Deboxt enum-typen naar integer. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Converteert enum-typen. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deboxt string-waarden. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deboxt string van geboxte waarde. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Deboxt object naar nullable-type. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Controleert of een object van onbekend type nullptr is. Overload voor niet-scalar-typen. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Controleert of een object van onbekend type nullptr is. Overload voor scalar-typen. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Converteert onbekend type naar [Object](../object/), waarbij zowel smart-pointer-type als waardetype-situaties worden afgehandeld. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Converteert onbekend type naar [Object](../object/), waarbij zowel smart-pointer-type als waardetype-situaties worden afgehandeld. |

## Zie ook

* Klasse [ObjectType](../objecttype/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)