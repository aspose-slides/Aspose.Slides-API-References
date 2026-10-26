---
title: "System::MemoryExtensions"
second_title: Aspose.Slides for C++ API 參考手冊
description: 提供針對 span 和陣列的記憶體操作的擴充方法。
type: docs
weight: 625
url: /zh-hant/system.memoryextensions/
---
提供用於 span 和陣列的記憶體操作擴充方法。

## 函式

| 函式 | 說明 |
| --- | --- |
| [Span](../system/span/)\<T\> [AsSpan](./asspan/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, **int32_t**, **int32_t**) | 從陣列建立 span。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [AsSpan](./asspan/)(const [String](../system/string/)\&, **int32_t**, **int32_t**) | 從字串建立唯讀 span。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TComparable\&) | 在已排序的 span 上執行二分搜尋。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自訂比較器在已排序的 span 上執行二分搜尋。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const TComparable\&) | 在可變的已排序 span 上執行二分搜尋。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自訂比較器在可變的已排序 span 上執行二分搜尋。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 找出兩個 span 之間共同前綴的長度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 找出可變 span 與唯讀 span 之間共同前綴的長度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 找出兩個可變 span 之間共同前綴的長度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 使用自訂相等比較器找出兩個 span 之間共同前綴的長度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 使用自訂相等比較器找出可變 span 與唯讀 span 之間共同前綴的長度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 使用自訂相等比較器找出兩個可變 span 之間共同前綴的長度。 |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 檢查唯讀 span 是否包含特定值。 |
| **bool** [Contains](./contains/)(const [Span](../system/span/)\<T\>\&, const T\&) | 檢查可變 span 是否包含特定值。 |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 檢查字元 span 是否包含另一個字元 span（使用指定的比較規則）。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 檢查唯讀 span 是否包含任一兩個值。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 檢查唯讀 span 是否包含任一三個值。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 檢查可變 span 是否包含任一兩個值。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 檢查可變 span 是否包含任一三個值。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 檢查唯讀 span 是否包含來自另一個 span 的任何值。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 檢查可變 span 是否包含來自唯讀 span 的任何值。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 檢查唯讀 span 是否包含除三個指定值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 檢查可變 span 是否包含除三個指定值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 檢查唯讀 span 是否包含除兩個指定值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 檢查可變 span 是否包含除兩個指定值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 檢查唯讀 span 是否包含除指定值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 檢查可變 span 是否包含除指定值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 檢查唯讀 span 是否包含除另一個 span 中的元素之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 檢查可變 span 是否包含除唯讀 span 中的元素之外的任何元素。 |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 檢查唯讀 span 是否包含超出指定範圍的任何元素。 |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 檢查可變 span 是否包含超出指定範圍的任何元素。 |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 檢查唯讀 span 是否包含在指定範圍內的任何元素。 |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 檢查可變 span 是否包含在指定範圍內的任何元素。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, [Span](../system/span/)\<T\>\&) | 將元素從陣列複製到 span。 |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 計算在唯讀 span 中出現的值的次數。 |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 計算一個 span 在另一個唯讀 span 中出現的次數。 |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const T\&) | 計算單一值在 Span<T> 中出現的次數。 |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 計算 ReadOnlySpan<T> 在 Span<T> 中出現的次數。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 判斷 ReadOnlySpan<T> 是否以單一值結尾。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 判斷 ReadOnlySpan<T> 是否以另一個 ReadOnlySpan<T> 結尾。 |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 判斷 Span<T> 是否以 ReadOnlySpan<T> 結尾。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 判斷 ReadOnlySpan<T> 是否以 Span<T> 結尾。 |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 判斷 Span<T> 是否以另一個 Span<T> 結尾。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用 StringComparison 判斷 ReadOnlySpan<char16_t> 是否以指定的值結尾。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在另一個 ReadOnlySpan<T> 中尋找 ReadOnlySpan<T> 值的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 在 ReadOnlySpan<T> 中尋找單一值的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 Span<T> 中尋找 ReadOnlySpan<T> 值的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | 在 Span<T> 中尋找單一值的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用 StringComparison 在 ReadOnlySpan<char16_t> 中尋找 ReadOnlySpan<char16_t> 值的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中找到任一兩個指定值首次出現的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中找到任一三個指定值首次出現的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 Span<T> 中找到任一兩個指定值首次出現的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 在 Span<T> 中找到任一三個指定值首次出現的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在另一個 ReadOnlySpan<T> 中找到來自 span 的任一值首次出現的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 Span<T> 中找到來自 span 的任一值首次出現的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 在 ReadOnlySpan<T> 中找到第一個不等於指定值的元素索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中找到第一個不等於任一兩個指定值的元素索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中找到第一個不等於任一三個指定值的元素索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 在 Span<T> 中找到第一個不等於指定值的元素索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 Span<T> 中找到第一個不等於任一兩個指定值的元素索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 在 Span<T> 中找到第一個不等於任一三個指定值的元素索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在一個值的 span 中找到第一個不等於任何值的元素索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 Span<T> 中的值的 span 中找到第一個不等於任何值的元素索引。 |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中找到第一個超出指定範圍的元素索引。 |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 Span<T> 中找到第一個超出指定範圍的元素索引。 |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中找到第一個位於指定範圍內的元素索引。 |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 Span<T> 中找到第一個位於指定範圍內的元素索引。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 span 中找到序列的最後一次出現。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 在 span 中找到單一值的最後一次出現。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在可變 span 中找到序列的最後一次出現。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | 在可變 span 中找到單一值的最後一次出現。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用指定的字串比較在 span 中找到值的最後一次出現。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 在 span 中找到任一三個指定值的最後一次出現。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 在可變 span 中找到任一三個指定值的最後一次出現。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 span 中找到任一兩個指定值的最後一次出現。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在可變 span 中找到任一兩個指定值的最後一次出現。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 span 中找到序列中任一值的最後一次出現。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在可變 span 中找到序列中任一值的最後一次出現。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 在可變 span 中找到可變序列中任一值的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 在 span 中尋找除三個指定值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 在可變 span 中尋找除三個指定值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 span 中尋找除兩個指定值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在可變 span 中尋找除兩個指定值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 在 span 中尋找除指定值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 在可變 span 中尋找除指定值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 span 中尋找除序列中的值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在可變 span 中尋找除序列中的值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 在可變 span 中尋找除可變序列中的值之外的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 span 中尋找超出指定範圍的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在可變 span 中尋找超出指定範圍的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 span 中尋找位於指定範圍內的任意元素的最後一次出現。 |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在可變 span 中尋找位於指定範圍內的任意元素的最後一次出現。 |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 判斷兩個 ReadOnlySpan 是否在記憶體中重疊，且不計算偏移量。 |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 判斷 [Span](../system/span/) 與 [ReadOnlySpan](../system/readonlyspan/) 是否在記憶體中重疊，且不計算偏移量。 |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | 判斷兩個 ReadOnlySpan 是否在記憶體中重疊，並計算偏移量。 |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | 判斷 [Span](../system/span/) 與 [ReadOnlySpan](../system/readonlyspan/) 是否在記憶體中重疊，並計算偏移量。 |
| void [Replace](./replace/)([Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 [Span](../system/span/) 中將所有出現的值取代為新值。 |
| void [Replace](./replace/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 將元素從來源複製到目標，並在複製過程中取代指定的值。 |
| void [Reverse](./reverse/)([Span](../system/span/)\<T\>\&) | 在原位反轉 [Span](../system/span/) 中元素的順序。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 以字典序比較兩個 ReadOnlySpan。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 以字典序比較 [Span](../system/span/) 與 [ReadOnlySpan](../system/readonlyspan/)。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 以字典序比較 [ReadOnlySpan](../system/readonlyspan/) 與 [Span](../system/span/)。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 判斷兩個 ReadOnlySpan 是否包含相同順序的相同元素。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 判斷 [Span](../system/span/) 與 [ReadOnlySpan](../system/readonlyspan/) 是否包含相同順序的相同元素。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 判斷兩個 ReadOnlySpan 是否使用自訂比較器包含相等的元素。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 判斷 [Span](../system/span/) 與 [ReadOnlySpan](../system/readonlyspan/) 是否使用自訂比較器包含相等的元素。 |
| void [Sort](./sort/)(const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自訂比較器對 [Span](../system/span/) 進行排序。 |
| void [Sort](./sort/)([Span](../system/span/)\<T\>\&) | 使用預設比較方式對 [Span](../system/span/) 進行排序。 |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自訂比較器對鍵值對進行排序（鍵和值一起排序） |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, [System::Comparison](../system/comparison/)\<TKey\>) | 使用比較委派對鍵值對進行排序。 |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&) | 使用預設比較方式對鍵值對進行排序。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 檢查 span 是否以指定的值開始。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 檢查 span 是否以指定的值 span 開始。 |
| **bool** [StartsWith](./startswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 檢查可變 span 是否以指定的唯讀值 span 開始。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 檢查唯讀 span 是否以指定的可變值 span 開始。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用字串比較檢查字符 span 是否以指定的值 span 開始。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<[String](../system/string/)\>\&, const char16_t *) | 檢查字串 span 是否以指定的字符陣列開始。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, T) | 從已型別化的 span 兩端裁剪指定的元素。 |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, T) | 從可變已型別化的 span 兩端裁剪指定的元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 從已型別化的 span 兩端裁剪指定的元素。 |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 從可變已型別化的 span 兩端裁剪指定的元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 從字符 span 兩端裁剪空白字符。 |
| [Span](../system/span/)\<char16_t\> [Trim](./trim/)([Span](../system/span/)\<char16_t\>\&) | 從可變字符 span 兩端裁剪空白字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 從已型別化的 span 末端裁剪指定的元素。 |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const T\&) | 從可變已型別化的 span 末端裁剪指定的元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 從已型別化的 span 末端裁剪指定的元素。 |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 從可變已型別化的 span 末端裁剪指定的元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 從字符 span 末端裁剪空白字符。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&) | 從可變字符 span 末端裁剪空白字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | 從字符 span 末端裁剪指定的字符。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, char16_t) | 從可變字符 span 末端裁剪指定的字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 從字符 span 末端裁剪指定的字符。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 從可變字符 span 末端裁剪指定的字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 從已型別化的 span 起始端裁剪指定的元素。 |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const T\&) | 從可變已型別化的 span 起始端裁剪指定的元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 從已型別化的 span 起始端裁剪指定的元素。 |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 從可變已型別化的 span 起始端裁剪指定的元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 從字符 span 起始端裁剪空白字符。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&) | 從可變字符 span 起始端裁剪空白字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | 從字符 span 起始端裁剪指定的字符。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, char16_t) | 從可變字符 span 起始端裁剪指定的字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 從字符 span 起始端裁剪指定的字符。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 從可變字符 span 起始端裁剪指定的字符。 |
| **int32_t** [CompareTo](./compareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用指定的字串比較規則比較兩個字符 span。 |
| **bool** [Equals](./equals/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用 StringComparison 比較兩個 ReadOnlySpan<char16_t> 是否相等。 |
| **bool** [IsWhiteSpace](./iswhitespace/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 檢查整個 span 是否僅包含空白字符。 |
| **int32_t** [ToLower](./tolower/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | 使用指定的文化將字符轉換為小寫。 |
| **int32_t** [ToLowerInvariant](./tolowerinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | 使用不變文化將字符轉換為小寫。 |
| **int32_t** [ToUpper](./toupper/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | 使用指定的文化將字符轉換為大寫。 |
| **int32_t** [ToUpperInvariant](./toupperinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | 使用不變文化將字符轉換為大寫。 |