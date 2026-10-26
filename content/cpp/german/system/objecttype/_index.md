---
title: ObjectType
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt statische Methoden bereit, die Objekt-Typ-Getter implementieren. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erzeugen.
type: docs
weight: 1158
url: /de/system/objecttype/
---
## ObjectType Klasse


Stellt statische Methoden bereit, die Objekt-Typ-Getter implementieren. Dies ist ein statischer Typ ohne Instanz-Dienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erzeugen.

```cpp
class ObjectType
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementiert typeof()-Übersetzung. Überladung für Smart-Pointer. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementiert typeof()-Übersetzung. Überladung für Strukturen. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implementiert typeof()-Übersetzung. Überladung für Ausnahmen. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementiert typeof()-Übersetzung. Überladung für primitive Typen. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implementiert typeof()-Übersetzung. Überladung für [Nullable](../nullable/) Typen. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für primitive Typen. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für Aufzählungs-Typen. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für Strukturen und Zeiger. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für Strukturen und Zeiger. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implementiert typeof()-Übersetzung. Überladung für String-Typ. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implementiert typeof()-Übersetzung. Überladung für **uint8_t**. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)