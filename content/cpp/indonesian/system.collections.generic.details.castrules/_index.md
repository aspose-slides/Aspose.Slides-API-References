---
title: "System::Collections::Generic::Details::CastRules"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 365
url: /id/system.collections.generic.details.castrules/
---
## Struktur

| Struct | Description |
| --- | --- |
| [CastType](./casttype/) | Berisi fungsi-fungsi untuk menentukan tipe cast. |
## Fungsi

| Function | Description |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | Mengkasting tipe sumber ke tipe hasil. Digunakan ketika tipe sumber dan tipe hasil sama. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | Mengkasting tipe sumber ke tipe hasil. Digunakan ketika tipe sumber dapat dikasting secara statis ke tipe hasil. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | Mengkasting tipe sumber ke tipe hasil. Digunakan ketika tipe tidak sama dan tipe sumber tidak dapat dikasting secara statis ke tipe hasil. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | Mengkasting tipe sumber ke tipe hasil. Digunakan ketika tipe sumber dibungkus ke instance kelas [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | Mengkasting tipe sumber ke tipe hasil. Digunakan ketika tipe sumber dibongkar dari instance kelas [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | Mengkasting tipe sumber ke tipe hasil. Digunakan ketika tipe sumber dibungkus ke instance kelas [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | Mengkasting tipe sumber ke tipe hasil. Digunakan ketika tipe sumber dibongkar dari instance kelas [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | Mengkasting tipe sumber ke tipe hasil. Digunakan ketika casting tidak valid atau konversi bersifat eksplisit. |
| **bool** [IsNull](./isnull/)(T) | Memeriksa bahwa nilai yang direpresentasikan adalah nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | Memeriksa bahwa nilai yang direpresentasikan adalah nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | Memeriksa bahwa nilai yang direpresentasikan adalah nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | Memeriksa kemungkinan casting. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | Memeriksa kemungkinan casting. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | Memeriksa kemungkinan casting. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | Memeriksa kemungkinan casting. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | Memeriksa kemungkinan casting. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | Memeriksa kemungkinan casting. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | Memeriksa kemungkinan casting. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | Memeriksa kemungkinan casting. |