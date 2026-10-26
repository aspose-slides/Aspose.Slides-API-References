---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 365
url: /hu/system.collections.generic.details.castrules/
---
## Struktúrák

| Struktúra | Leírás |
| --- | --- |
| [CastType](./casttype/) | Tartalmazza a típuskonverzió meghatározásához szükséges függvényeket. |
## Függvények

| Függvény | Leírás |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Átkonvertálja a forrástípust a céltípusra. Akkor használható, ha a forrás- és a céltípus azonos. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Átkonvertálja a forrástípust a céltípusra. Akkor használható, ha a forrástípust statikusan lehet a céltípusra átkonvertálni. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Átkonvertálja a forrástípust a céltípusra. Akkor használható, ha a típusok nem egyeznek, és a forrástípust nem lehet statikusan a céltípusra átkonvertálni. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Átkonvertálja a forrástípust a céltípusra. Akkor használható, ha a forrástípust a [Nullable](../system/nullable/) osztálypéldányba csomagolják. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Átkonvertálja a forrástípust a céltípusra. Akkor használható, ha a forrástípust a [Nullable](../system/nullable/) osztálypéldányból csomagolnak ki. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Átkonvertálja a forrástípust a céltípusra. Akkor használható, ha a forrástípust a [Object](../system/object/) osztálypéldányba csomagolják. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Átkonvertálja a forrástípust a céltípusra. Akkor használható, ha a forrástípust a [Object](../system/object/) osztálypéldányból csomagolnak ki. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Átkonvertálja a forrástípust a céltípusra. Akkor használható, ha az átkonvertálás érvénytelen vagy a konverzió explicit. |
| **bool** [IsNull](./isnull/)(T) | Ellenőrzi, hogy a képviselt érték nullptr-e. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Ellenőrzi, hogy a képviselt érték nullptr-e. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Ellenőrzi, hogy a képviselt érték nullptr-e. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Ellenőrzi az átkonvertálás lehetőségét. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Ellenőrzi az átkonvertálás lehetőségét. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Ellenőrzi az átkonvertálás lehetőségét. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Ellenőrzi az átkonvertálás lehetőségét. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Ellenőrzi az átkonvertálás lehetőségét. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Ellenőrzi az átkonvertálás lehetőségét. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Ellenőrzi az átkonvertálás lehetőségét. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Ellenőrzi az átkonvertálás lehetőségét. |