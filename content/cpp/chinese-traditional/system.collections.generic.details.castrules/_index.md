---
title: "System::Collections::Generic::Details::CastRules"
second_title: Aspose.Slides for C++ API 參考
description: 
type: docs
weight: 365
url: /zh-hant/system.collections.generic.details.castrules/
---
## 結構

| 結構體 | 說明 |
| --- | --- |
| [CastType](./casttype/) | 包含用於判斷轉型類型的函式。 |
## 函式

| 函式 | 說明 |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | 將來源類型轉換為結果類型。用於來源類型與結果類型相同的情況。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | 將來源類型轉換為結果類型。用於來源類型可以靜態轉換為結果類型的情況。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | 將來源類型轉換為結果類型。用於類型不同且來源類型無法靜態轉換為結果類型的情況。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | 將來源類型轉換為結果類型。用於來源類型被裝箱至 [Nullable](../system/nullable/) 類別實例的情況。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | 將來源類型轉換為結果類型。用於來源類型從 [Nullable](../system/nullable/) 類別實例解除裝箱的情況。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | 將來源類型轉換為結果類型。用於來源類型被裝箱至 [Object](../system/object/) 類別實例的情況。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | 將來源類型轉換為結果類型。用於來源類型從 [Object](../system/object/) 類別實例解除裝箱的情況。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | 將來源類型轉換為結果類型。用於轉型無效或轉換為顯式的情況。 |
| **bool** [IsNull](./isnull/)(T) | 檢查所代表的值是否為 nullptr。 |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | 檢查所代表的值是否為 nullptr。 |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | 檢查所代表的值是否為 nullptr。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | 檢查轉型的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | 檢查轉型的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | 檢查轉型的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | 檢查轉型的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | 檢查轉型的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | 檢查轉型的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | 檢查轉型的可能性。 |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | 檢查轉型的可能性。 |