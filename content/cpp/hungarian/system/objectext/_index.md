---
title: ObjectExt
second_title: Aspose.Slides for C++ API referencia
description: Statikus metódusokat biztosít, amelyek a C# Object metódusokat emulálják, amelyek nem-Object C++ típusokra (karakterláncok, számok stb.) hívhatóak. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha nem szabad példányokat létrehozni ebből semmilyen módon.
type: docs
weight: 1145
url: /hu/system/objectext/
---
## ObjectExt osztály


Statikus módszereket biztosít, amelyek a C# [Object](../object/) metódusokat emulálják, amelyek nem-Object C++ típusokra (karakterláncok, számok stb.) hívhatóak. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha nem szabad példányokat létrehozni ebből semmilyen módon.

```cpp
class ObjectExt : public System::ObjectType
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Átkonvertálja a tömb alaptípusú értékeit (amelyet a C# implicit módon tesz, de a C++ látszólag nem). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Dobozolja az értéktípusokat a [Object](../object/)-re konvertáláshoz. Megvalósítás enum típusokhoz. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Dobozolja az értéktípusokat a [Object](../object/)-re konvertáláshoz. Megvalósítás nem enum típusokhoz. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Dobozolja a [Nullable](../nullable/) típusokat a [Object](../object/)-re konvertáláshoz. |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Dobozolja a karakterlánc értékeket. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Dobozolja az enum típusokat [Object](../object/)-ként terjesztésre. |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | A '??' operátor fordításának megvalósítása nem-nullázható típusokhoz. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | A '??' operátor fordításának megvalósítása nullable típusokhoz. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | A '??=' operátor fordításának megvalósítása. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | A '??' operátor fordításának megvalósítása nem-nullázható típusokhoz. Túlterhelés, ha az RT2 konvertálható az RT1-re. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Helyettesítés a C# [Object.Equals](../object/equals/) hívásokra, amelyek minden C++ típusnál működnek. Túlterhelés okos mutató típusokhoz. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Helyettesítés a C# [Object.Equals](../object/equals/) hívásokra, amelyek minden C++ típusnál működnek. Túlterhelés szerkezet típusokhoz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Helyettesítés a C# [Object.Equals](../object/equals/) hívásokra, amelyek minden C++ típusnál működnek. Túlterhelés skalár típusokhoz. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Helyettesítés a C# [Object.Equals](../object/equals/) hívásokra, amelyek minden C++ típusnál működnek. Túlterhelés karakterlánc literálokra, karakterlánc összehasonlítással. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Megvalósítja a [GetHashCode()](./gethashcode/) hívásokat; működik mind a [Object](../object/) alosztályokon, mind a nem kapcsolódó típusokon. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Megvalósítja a typeof() fordítást. Túlterhelés okos mutatókhoz. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Megvalósítja a typeof() fordítást. Túlterhelés szerkezetekhez. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Megvalósítja a typeof() fordítást. Túlterhelés kivételekhez. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Megvalósítja a typeof() fordítást. Túlterhelés primitív típusokhoz. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Megvalósítja a typeof() fordítást. Túlterhelés [Nullable](../nullable/) típusokhoz. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés primitív típusokhoz. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés enum típusokhoz. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés szerkezetekhez és mutatókhoz. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés [Nullable](../nullable/)-hez. |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés MutlicastDelegate-hez. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés szerkezetekhez és mutatókhoz. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Megvalósítja a typeof() fordítást. Túlterhelés karakterlánc típushoz. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés **uint8_t**-hez. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés **uint8_t**-hez. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés **uint8_t**-hez. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés **uint8_t**-hez. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés **uint8_t**-hez. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Megvalósítja a typeof() fordítást. Túlterhelés **uint8_t**-hez. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Megvalósítja az 'is' operátor fordítását. Specializáció a dobozolható (érték) típusokra, amelyek pontosan ilyenek. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Megvalósítja az 'is' operátor fordítását. Specializáció mutató típusokra, amelyek a 'final' osztályokra optimalizáltak. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Megvalósítja az 'is' operátor fordítását. Specializáció mutató típusokra. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Megvalósítja az 'is' operátor fordítását. Specializáció érték típusokra. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Megvalósítja az 'is' operátor fordítását. Specializáció nem konvertálható típusokra. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció mutató típusokra. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció kivétel burkoló típusokra. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció nullable típusokra. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció dobozolható típusokra, ahol definiált az == operátor. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció dobozolható típusokra, ahol nincs definiált == operátor. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció érték típusokra, amelyek interfészekre vannak dobozolva. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció enum típusokra. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció enum típusokra gyenge mutatókkal. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Megvalósítja az 'is' operátor fordítását. Specializáció [Nullable](../nullable/) típusra. |
| static **bool** [Is](./is/)(const char16_t *) | Megvalósítja az 'is' operátor fordítását. Specializáció karakterlánc literálra. |
| static **bool** [Is](./is/)(**int32_t**) | Megvalósítja az 'is' operátor fordítását. Specializáció egész literálra. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Ellenőrzi, hogy az objektum dobozolt érték-e. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Átkonvertálja a [Object](../object/)-t ismeretlen típusra, kezelve mind az okos mutató típust, mind a bpxed értéket. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Átkonvertálja a [Object](../object/)-t ismeretlen típusra, kezelve az okos mutató típusú és dobozott érték helyzeteket. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Helyettesítés a C# ToString metódusra, amely minden C++ típuson működik. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Kicsomagolja az értéktípusokat a [Object](../object/)-re konvertálás után. Megvalósítás enum típusokhoz. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Kicsomagolja az értéktípusokat a [Object](../object/)-re konvertálás után. Megvalósítás nem-enum és nem-nullázható típusokhoz. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Kicsomagolja az értéktípusokat a [Object](../object/)-re konvertálás után. Megvalósítás nem-enum és nem-nullázható típusokhoz. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Kicsomagolja az enum típusokat egész számmá. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Átkonvertálja az enum típusokat. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Kicsomagolja a karakterlánc értékeket. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Kicsomagolja a karakterláncot a dobozott értékből. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Kicsomagolja az objektumot nullable típusra. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Ellenőrzi, hogy az ismeretlen típusú objektum nullptr-e. Túlterhelés nem-skalár típusokhoz. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Ellenőrzi, hogy az ismeretlen típusú objektum nullptr-e. Túlterhelés skalár típusokhoz. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Átkonvertálja az ismeretlen típust a [Object](../object/)-re, kezelve az okos mutató típusú és érték típusú helyzeteket. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Átkonvertálja az ismeretlen típust a [Object](../object/)-re, kezelve az okos mutató típusú és érték típusú helyzeteket. |

## Lásd még

* Osztály [ObjectType](../objecttype/)
* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)