---
title: ObjectExt
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Poskytuje statické metody, které napodobují metody C# Object volané pro netypové C++ typy (řetězce, čísla atd.). Jedná se o statický typ bez služeb instance. Neměli byste jej nikdy vytvářet žádnými prostředky.
type: docs
weight: 1145
url: /cs/system/objectext/
---
## ObjectExt třída


Poskytuje statické metody, které napodobují metody C# [Object](../object/) volané pro netypové C++ typy (řetězce, čísla atd.). Jedná se o statický typ bez služeb instance. Neměli byste nikdy vytvářet jeho instance žádným způsobem.

```cpp
class ObjectExt : public System::ObjectType
```

## Metody

| Method | Description |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Převádí základní hodnoty pole (což C# dělá implicitně, ale C++ zřejmě ne). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Zabaluje typy hodnot pro převod na [Object](../object/). Implementace pro výčtové typy. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Zabaluje typy hodnot pro převod na [Object](../object/). Implementace pro typy, které nejsou výčtové. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Zabaluje typy [Nullable](../nullable/) pro převod na [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Zabaluje řetězcové hodnoty. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Zabaluje výčtové typy pro propagaci jako [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementace překladu operátoru '??' pro nenulovatelné typy. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementace překladu operátoru '??' pro nulovatelné typy. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementace překladu operátoru '??='. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementace překladu operátoru '??' pro nenulovatelné typy. Přetížení pro případ, kdy je RT2 konvertibilní na RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Náhrada za volání C# [Object.Equals](../object/equals/) fungující pro libovolný typ v C++. Přetížení pro typy chytrých ukazatelů. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Náhrada za volání C# [Object.Equals](../object/equals/) fungující pro libovolný typ v C++. Přetížení pro typy struktur. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Náhrada za volání C# [Object.Equals](../object/equals/) fungující pro libovolný typ v C++. Přetížení pro skalární typy. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Náhrada za volání C# [Object.Equals](../object/equals/) fungující pro libovolný typ v C++. Přetížení pro řetězcový literál s porovnáním řetězců. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Emuluje porovnání plovoucí řádové čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovna žádné hodnotě, včetně NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Emuluje porovnání typu double ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovna žádné hodnotě, včetně NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implementuje volání [GetHashCode()](./gethashcode/); funguje jak na podtřídách [Object](../object/), tak na nesouvisejících typech. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementuje překlad typeof(). Přetížení pro chytré ukazatele. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementuje překlad typeof(). Přetížení pro struktury. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementuje překlad typeof(). Přetížení pro výjimky. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementuje překlad typeof(). Přetížení pro primitivní typy. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementuje překlad typeof(). Přetížení pro typy [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro primitivní typy. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro výčtové typy. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro struktury a ukazatele. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro MulticastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro struktury a ukazatele. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implementuje překlad typeof(). Přetížení pro řetězcový typ. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje překlad typeof(). Přetížení pro **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implementuje překlad operátoru 'is'. Specializace pro zabalené (value) typy, které jsou přesně tím, čím jsou. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementuje překlad operátoru 'is'. Specializace pro typy ukazatelů optimalizovaná pro třídy 'final'. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementuje překlad operátoru 'is'. Specializace pro typy ukazatelů. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementuje překlad operátoru 'is'. Specializace pro typy hodnot. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementuje překlad operátoru 'is'. Specializace pro typy nelze převést. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementuje překlad operátoru 'is'. Specializace pro typy ukazatelů. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implementuje překlad operátoru 'is'. Specializace pro typy obalů výjimek. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementuje překlad operátoru 'is'. Specializace pro nullable typy. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementuje překlad operátoru 'is'. Specializace pro zabalené typy s definovaným operátorem ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementuje překlad operátoru 'is'. Specializace pro zabalené typy bez definovaného operátoru ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implementuje překlad operátoru 'is'. Specializace pro typy hodnot zabalené do rozhraní. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementuje překlad operátoru 'is'. Specializace pro výčtové typy. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implementuje překlad operátoru 'is'. Specializace pro výčtové typy vůči slabým ukazatelům. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implementuje překlad operátoru 'is'. Specializace pro typ [Nullable](../nullable/). |
| static **bool** [Is](./is/)(const char16_t *) | Implementuje překlad operátoru 'is'. Specializace pro řetězcový literál. |
| static **bool** [Is](./is/)(**int32_t**) | Implementuje překlad operátoru 'is'. Specializace pro celočíselný literál. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Kontroluje, zda je objekt zabalenou hodnotou. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Převádí [Object](../object/) na neznámý typ, přičemž řeší jak typ chytrého ukazatele, tak zabalenou hodnotu. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Převádí [Object](../object/) na neznámý typ, přičemž řeší jak typ chytrého ukazatele, tak zabalenou hodnotu. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Náhrada za metodu C# ToString, aby fungovala na libovolném typu C++. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Rozbalí typy hodnot po převodu na [Object](../object/). Implementace pro výčtové typy. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Rozbalí typy hodnot po převodu na [Object](../object/). Implementace pro typy, které nejsou výčtové a nejsou nullable. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Rozbalí typy hodnot po převodu na [Object](../object/). Implementace pro typy, které nejsou výčtové a nejsou nullable. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Rozbalí výčtové typy na celé číslo. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Převádí výčtové typy. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Rozbalí řetězcové hodnoty. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Rozbalí řetězec ze zabalené hodnoty. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Rozbalí objekt na nullable typ. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Kontroluje, zda je objekt neznámého typu nullptr. Přetížení pro typy, které nejsou skalární. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Kontroluje, zda je objekt neznámého typu nullptr. Přetížení pro skalární typy. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Převádí neznámý typ na [Object](../object/), přičemž řeší jak typ chytrého ukazatele, tak typ hodnoty. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Převádí neznámý typ na [Object](../object/), přičemž řeší jak typ chytrého ukazatele, tak typ hodnoty. |

## Viz také

* Třída [ObjectType](../objecttype/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)