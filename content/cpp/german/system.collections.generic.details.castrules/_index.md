---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 365
url: /de/system.collections.generic.details.castrules/
---
## Strukturen

| Struktur | Beschreibung |
| --- | --- |
| [CastType](./casttype/) | Enthält die Funktionen zur Bestimmung des Cast-Typs. |
## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn Quell- und Ergebnistyp identisch sind. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp statisch in den Ergebnistyp konvertiert werden kann. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn die Typen nicht identisch sind und der Quelltyp nicht statisch in den Ergebnistyp konvertiert werden kann. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp in eine Instanz der Klasse [Nullable](../system/nullable/) geboxt wird. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp aus einer Instanz der Klasse [Nullable](../system/nullable/) entboxt wird. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp in eine Instanz der Klasse [Object](../system/object/) geboxt wird. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp aus einer Instanz der Klasse [Object](../system/object/) entboxt wird. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn das Casting ungültig ist oder die Konvertierung explizit erfolgt. |
| **bool** [IsNull](./isnull/)(T) | Überprüft, ob der dargestellte Wert nullptr ist. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Überprüft, ob der dargestellte Wert nullptr ist. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Überprüft, ob der dargestellte Wert nullptr ist. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Prüft die Cast-Möglichkeit. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Prüft die Cast-Möglichkeit. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Prüft die Cast-Möglichkeit. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Prüft die Cast-Möglichkeit. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Prüft die Cast-Möglichkeit. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Prüft die Cast-Möglichkeit. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Prüft die Cast-Möglichkeit. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Prüft die Cast-Möglichkeit. |