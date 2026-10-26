---
title: ObjectExt
second_title: Aspose.Slides per l'API di riferimento C++ 
description: Fornisce metodi statici che emulano i metodi C# Object chiamati per tipi C++ non-Object (stringhe, numeri, ecc.). Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso con alcun mezzo.
type: docs
weight: 1145
url: /it/system/objectext/
---
## ObjectExt classe


Fornisce metodi statici che emulano i metodi C# [Object](../object/) chiamati per tipi C++ non-Object (stringhe, numeri, ecc.). Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso con alcun mezzo.

```cpp
class ObjectExt : public System::ObjectType
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Converte valori fondamentali di array (che C# fa implicitamente ma C++ apparentemente no). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Incapsula i tipi valore per la conversione a [Object](../object/). Implementazione per tipi enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Incapsula i tipi valore per la conversione a [Object](../object/). Implementazione per tipi non enum. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Incapsula i tipi [Nullable](../nullable/) per la conversione a [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Incapsula valori stringa. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Incapsula i tipi enum per essere propagati come [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementazione della traduzione dell'operatore '??' per tipi non nullabili. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementazione della traduzione dell'operatore '??' per tipi nullable. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementazione della traduzione dell'operatore '??='. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementazione della traduzione dell'operatore '??' per tipi non nullabili. Sovraccarico per il caso in cui RT2 è convertibile in RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Sostituzione per le chiamate C# [Object.Equals](../object/equals/) che funzionano per qualsiasi tipo in C++. Sovraccarico per tipi puntatore intelligente. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Sostituzione per le chiamate C# [Object.Equals](../object/equals/) che funzionano per qualsiasi tipo in C++. Sovraccarico per tipi struttura. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Sostituzione per le chiamate C# [Object.Equals](../object/equals/) che funzionano per qualsiasi tipo in C++. Sovraccarico per tipi scalari. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Sostituzione per le chiamate C# [Object.Equals](../object/equals/) che funzionano per qualsiasi tipo in C++. Sovraccarico per letterale stringa con confronto stringa. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implementa le chiamate [GetHashCode()](./gethashcode/); funziona sia sui sottoclassi [Object](../object/) sia su tipi non correlati. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementa la traduzione di typeof(). Sovraccarico per puntatori intelligenti. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementa la traduzione di typeof(). Sovraccarico per strutture. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementa la traduzione di typeof(). Sovraccarico per eccezioni. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementa la traduzione di typeof(). Sovraccarico per tipi primitivi. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementa la traduzione di typeof(). Sovraccarico per tipi [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per tipi primitivi. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per tipi enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per strutture e puntatori. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per strutture e puntatori. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implementa la traduzione di typeof(). Sovraccarico per tipo stringa. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi incapsulabili (valore) che sono esattamente ciò che sono. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi puntatore ottimizzati per classi 'final'. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi puntatore. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi valore. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi non convertibili. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi puntatore. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi wrapper di eccezione. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi nullable. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi incapsulabili con operatore == definito. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi incapsulabili senza operatore == definito. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per tipi valore incapsulati in interfacce. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi enum. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per i tipi enum vs puntatori deboli. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implementa la traduzione dell'operatore 'is'. Specializzazione per il tipo [Nullable](../nullable/). |
| static **bool** [Is](./is/)(const char16_t *) | Implementa la traduzione dell'operatore 'is'. Specializzazione per letterale stringa. |
| static **bool** [Is](./is/)(**int32_t**) | Implementa la traduzione dell'operatore 'is'. Specializzazione per letterale intero. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Verifica se l'oggetto è un valore incapsulato. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Converte [Object](../object/) in tipo sconosciuto, gestendo sia il tipo puntatore intelligente sia le situazioni di valore incapsulato. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Converte [Object](../object/) in tipo sconosciuto, gestendo sia il tipo puntatore intelligente sia le situazioni di valore incapsulato. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Sostituzione per il metodo C# ToString per funzionare su qualsiasi tipo C++. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deincapsula i tipi valore dopo la conversione a [Object](../object/). Implementazione per tipi enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deincapsula i tipi valore dopo la conversione a [Object](../object/). Implementazione per tipi non enum e non nullabili. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deincapsula i tipi valore dopo la conversione a [Object](../object/). Implementazione per tipi non enum e non nullabili. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Deincapsula i tipi enum in intero. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Converte i tipi enum. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deincapsula valori stringa. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Deincapsula stringa da valore incapsulato. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Deincapsula oggetto in tipo nullable. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Verifica se l'oggetto di tipo sconosciuto è nullptr. Sovraccarico per tipi non scalari. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Verifica se l'oggetto di tipo sconosciuto è nullptr. Sovraccarico per tipi scalari. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Converte il tipo sconosciuto in [Object](../object/), gestendo sia il tipo puntatore intelligente sia le situazioni di tipo valore. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Converte il tipo sconosciuto in [Object](../object/), gestendo sia il tipo puntatore intelligente sia le situazioni di tipo valore. |

## Vedi anche

* Classe [ObjectType](../objecttype/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)