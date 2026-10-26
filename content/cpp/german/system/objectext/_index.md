---
title: ObjectExt
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt statische Methoden bereit, die C#-Objekt-Methoden für Nicht-Objekt-C++-Typen (Zeichenketten, Zahlen usw.) nachahmen. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 1145
url: /de/system/objectext/
---
## ObjectExt Klasse


Stellt statische Methoden bereit, die C# [Object](../object/)-Methoden nachahmen, die für nicht-Object C++-Typen (Zeichenketten, Zahlen usw.) aufgerufen werden. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class ObjectExt : public System::ObjectType
```

## Methoden

| Method | Description |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Konvertiert grundlegende Array-Werte (die C# implizit erledigt, C++ jedoch anscheinend nicht). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Kapselt Werttypen zur Konvertierung nach [Object](../object/). Implementierung für Aufzählungstypen. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Kapselt Werttypen zur Konvertierung nach [Object](../object/). Implementierung für Nicht-Aufzählungstypen. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Kapselt [Nullable](../nullable/)-Typen zur Konvertierung nach [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Kapselt Zeichenkettenwerte. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Kapselt Aufzählungstypen zur Weitergabe als [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementierung der '??'-Operator-Übersetzung für nicht-nullbare Typen. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementierung der '??'-Operator-Übersetzung für nullable Typen. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementierung der '??='-Operator-Übersetzung. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementierung der '??'-Operator-Übersetzung für nicht-nullbare Typen. Überladung für den Fall, dass RT2 in RT1 konvertierbar ist. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Ersetzung für C# [Object.Equals](../object/equals/)-Aufrufe, die für jeden Typ in C++ funktionieren. Überladung für Smart-Pointer-Typen. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Ersetzung für C# [Object.Equals](../object/equals/)-Aufrufe, die für jeden Typ in C++ funktionieren. Überladung für Strukturtypen. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Ersetzung für C# [Object.Equals](../object/equals/)-Aufrufe, die für jeden Typ in C++ funktionieren. Überladung für Skalartypen. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Ersetzung für C# [Object.Equals](../object/equals/)-Aufrufe, die für jeden Typ in C++ funktionieren. Überladung für Zeichenkettenliteral mit Zeichenkettenvergleich. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Emuliert C#-ähnlichen Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Emuliert C#-ähnlichen Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implementiert [GetHashCode()](./gethashcode/)-Aufrufe; funktioniert sowohl bei [Object](../object/)-Unterklassen als auch bei nicht verwandten Typen. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementiert typeof()-Übersetzung. Überladung für Smart-Pointer. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementiert typeof()-Übersetzung. Überladung für Strukturen. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementiert typeof()-Übersetzung. Überladung für Ausnahmen. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementiert typeof()-Übersetzung. Überladung für primitive Typen. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementiert typeof()-Übersetzung. Überladung für [Nullable](../nullable/)-Typen. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für primitive Typen. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für Aufzählungstypen. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für Strukturen und Zeiger. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für MulticastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für Strukturen und Zeiger. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implementiert typeof()-Übersetzung. Überladung für Zeichenkettentyp. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für boxbare (Wert-)Typen, die genau das sind. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Zeigertypen, optimiert für 'final'-Klassen. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Zeigertypen. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Werttypen. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für nicht konvertierbare Typen. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Zeigertypen. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Ausnahme-Wrapper-Typen. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Nullable-Typen. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für boxbare Typen mit definiertem ==-Operator. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für boxbare Typen ohne definierten ==-Operator. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Werttypen, die zu Schnittstellen geboxt werden. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Aufzählungstypen. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Aufzählungstypen vs. schwache Zeiger. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für [Nullable](../nullable/)-Typ. |
| static **bool** [Is](./is/)(const char16_t *) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Zeichenkettenliteral. |
| static **bool** [Is](./is/)(**int32_t**) | Implementiert die 'is'-Operator-Übersetzung. Spezialisierung für Ganzzahl-Literal. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Prüft, ob das Objekt ein geboxter Wert ist. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Konvertiert [Object](../object/) zu einem unbekannten Typ, behandelt sowohl Smart-Pointer-Typen als auch geboxte Wertsituationen. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Konvertiert [Object](../object/) zu einem unbekannten Typ, behandelt sowohl Smart-Pointer-Typen als auch geboxte Wertsituationen. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Ersetzung für die C#-ToString-Methode, damit sie für jeden C++-Typ funktioniert. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Entkapselt Werttypen nach der Konvertierung nach [Object](../object/). Implementierung für Aufzählungstypen. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Entkapselt Werttypen nach der Konvertierung nach [Object](../object/). Implementierung für Nicht-Aufzählungs- und Nicht-Nullable-Typen. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Entkapselt Werttypen nach der Konvertierung nach [Object](../object/). Implementierung für Nicht-Aufzählungs- und Nicht-Nullable-Typen. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Entkapselt Aufzählungstypen zu Ganzzahlen. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Konvertiert Aufzählungstypen. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Entkapselt Zeichenkettenwerte. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Entkapselt Zeichenketten aus geboxtem Wert. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Entkapselt Objekt zu Nullable-Typ. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Prüft, ob ein unbekanntes Typ-Objekt nullptr ist. Überladung für nicht-skalare Typen. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Prüft, ob ein unbekanntes Typ-Objekt nullptr ist. Überladung für skalare Typen. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Konvertiert unbekannten Typ zu [Object](../object/), behandelt sowohl Smart-Pointer-Typen als auch Werttypen. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Konvertiert unbekannten Typ zu [Object](../object/), behandelt sowohl Smart-Pointer-Typen als auch Werttypen. |

## Siehe auch

* Klasse [ObjectType](../objecttype/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)