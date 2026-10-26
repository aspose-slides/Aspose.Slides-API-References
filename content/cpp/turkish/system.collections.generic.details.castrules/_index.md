---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 365
url: /tr/system.collections.generic.details.castrules/
---
## Yapılar

| Yapı | Açıklama |
| --- | --- |
| [CastType](./casttype/) | Cast tipini belirlemek için fonksiyonları içerir. |
## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Kaynak türünü sonuç türüne dönüştürür. Kaynak ve sonuç türleri aynı olduğunda kullanılır. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Kaynak türünü sonuç türüne dönüştürür. Kaynak türü, sonuç türüne statik olarak dönüştürülebildiğinde kullanılır. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Kaynak türünü sonuç türüne dönüştürür. Türler aynı olmadığında ve kaynak türü sonuç türüne statik olarak dönüştürülemediğinde kullanılır. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Kaynak türünü sonuç türüne dönüştürür. Kaynak türü [Nullable](../system/nullable/) sınıf örneğine kutulanırken kullanılır. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Kaynak türünü sonuç türüne dönüştürür. Kaynak türü [Nullable](../system/nullable/) sınıf örneğinden kutudan çıkarılırken kullanılır. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Kaynak türünü sonuç türüne dönüştürür. Kaynak türü [Object](../system/object/) sınıf örneğine kutulanırken kullanılır. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Kaynak türünü sonuç türüne dönüştürür. Kaynak türü [Object](../system/object/) sınıf örneğinden kutudan çıkarılırken kullanılır. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Kaynak türünü sonuç türüne dönüştürür. Dönüştürme geçersiz olduğunda veya dönüşüm açık olduğunda kullanılır. |
| **bool** [IsNull](./isnull/)(T) | Temsili değerin nullptr olduğunu kontrol eder. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Temsili değerin nullptr olduğunu kontrol eder. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Temsili değerin nullptr olduğunu kontrol eder. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Dönüştürme olasılığını kontrol eder. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Dönüştürme olasılığını kontrol eder. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Dönüştürme olasılığını kontrol eder. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Dönüştürme olasılığını kontrol eder. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Dönüştürme olasılığını kontrol eder. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Dönüştürme olasılığını kontrol eder. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Dönüştürme olasılığını kontrol eder. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Dönüştürme olasılığını kontrol eder. |