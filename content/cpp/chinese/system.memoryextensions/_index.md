---
title: "System::MemoryExtensions"
second_title: Aspose.Slides for C++ API 参考
description: 提供用于 span 和数组的内存操作的扩展方法。
type: docs
weight: 625
url: /zh/system.memoryextensions/
---
提供用于 span 和数组的内存操作的扩展方法。

## 函数

| 函数 | 描述 |
| --- | --- |
| [Span](../system/span/)\<T\> [AsSpan](./asspan/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, **int32_t**, **int32_t**) | 从数组创建一个 span。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [AsSpan](./asspan/)(const [String](../system/string/)\&, **int32_t**, **int32_t**) | 从字符串创建只读 span。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TComparable\&) | 在已排序的 span 上执行二分查找。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自定义比较器在已排序的 span 上执行二分查找。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const TComparable\&) | 在可变已排序的 span 上执行二分查找。 |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自定义比较器在可变已排序的 span 上执行二分查找。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 查找两个 span 之间公共前缀的长度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 查找可变 span 与只读 span 之间公共前缀的长度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 查找两个可变 span 之间公共前缀的长度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 使用自定义相等比较器查找两个 span 之间公共前缀的长度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 使用自定义相等比较器查找可变 span 与只读 span 之间公共前缀的长度。 |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 使用自定义相等比较器查找两个可变 span 之间公共前缀的长度。 |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 检查只读 span 是否包含特定值。 |
| **bool** [Contains](./contains/)(const [Span](../system/span/)\<T\>\&, const T\&) | 检查可变 span 是否包含特定值。 |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 检查字符 span 是否包含另一个字符 span（使用指定的比较规则）。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 检查只读 span 是否包含两个值中的任意一个。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 检查只读 span 是否包含三个值中的任意一个。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 检查可变 span 是否包含两个值中的任意一个。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 检查可变 span 是否包含三个值中的任意一个。 |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 检查只读 span 是否包含来自另一个 span 的任意值。 |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 检查可变 span 是否包含来自只读 span 的任意值。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 检查只读 span 是否包含除指定的三个值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 检查可变 span 是否包含除指定的三个值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 检查只读 span 是否包含除指定的两个值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 检查可变 span 是否包含除指定的两个值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 检查只读 span 是否包含除指定值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 检查可变 span 是否包含除指定值之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 检查只读 span 是否包含除另一个 span 中的元素之外的任何元素。 |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 检查可变 span 是否包含除只读 span 中的元素之外的任何元素。 |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 检查只读 span 是否包含指定范围之外的任何元素。 |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 检查可变 span 是否包含指定范围之外的任何元素。 |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 检查只读 span 是否包含指定范围内的任何元素。 |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 检查可变 span 是否包含指定范围内的任何元素。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, [Span](../system/span/)\<T\>\&) | 将数组中的元素复制到 span。 |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 计算只读 span 中值的出现次数。 |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 计算一个 span 在另一个只读 span 中出现的次数。 |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const T\&) | 计算 Span<T> 中单个值的出现次数。 |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 计算 Span<T> 中 ReadOnlySpan<T> 的出现次数。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 确定 ReadOnlySpan<T> 是否以单个值结尾。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 确定 ReadOnlySpan<T> 是否以另一个 ReadOnlySpan<T> 结尾。 |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 确定 Span<T> 是否以 ReadOnlySpan<T> 结尾。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 确定 ReadOnlySpan<T> 是否以 Span<T> 结尾。 |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 确定 Span<T> 是否以另一个 Span<T> 结尾。 |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用 StringComparison 确定 ReadOnlySpan<char16_t> 是否以指定值结尾。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在另一个 ReadOnlySpan<T> 中查找 ReadOnlySpan<T> 值的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 在 ReadOnlySpan<T> 中查找单个值的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 Span<T> 中查找 ReadOnlySpan<T> 值的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | 在 Span<T> 中查找单个值的索引。 |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用 StringComparison 在 ReadOnlySpan<char16_t> 中查找 ReadOnlySpan<char16_t> 值的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中查找任意两个指定值的首次出现位置的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中查找任意三个指定值的首次出现位置的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 Span<T> 中查找任意两个指定值的首次出现位置的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 在 Span<T> 中查找任意三个指定值的首次出现位置的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在另一个 ReadOnlySpan<T> 中查找来自 span 的任意值的首次出现位置的索引。 |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 Span<T> 中查找来自 span 的任意值的首次出现位置的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 在 ReadOnlySpan<T> 中查找第一个不等于指定值的元素的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中查找第一个不等于任意两个指定值的元素的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中查找第一个不等于任意三个指定值的元素的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 在 Span<T> 中查找第一个不等于指定值的元素的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 Span<T> 中查找第一个不等于任意两个指定值的元素的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 在 Span<T> 中查找第一个不等于任意三个指定值的元素的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在一个值的 span 中查找第一个不等于任何值的元素的索引。 |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 Span<T> 中的值 span 中查找第一个不等于任何值的元素的索引。 |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中查找第一个超出指定范围的元素的索引。 |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 Span<T> 中查找第一个超出指定范围的元素的索引。 |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 ReadOnlySpan<T> 中查找第一个位于指定范围内的元素的索引。 |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 Span<T> 中查找第一个位于指定范围内的元素的索引。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 span 中查找序列的最后一次出现。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 在 span 中查找单个值的最后一次出现。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在可变 span 中查找序列的最后一次出现。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | 在可变 span 中查找单个值的最后一次出现。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用指定的字符串比较在 span 中查找值的最后一次出现。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 在 span 中查找任意三个指定值的最后一次出现。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 在可变 span 中查找任意三个指定值的最后一次出现。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 span 中查找任意两个指定值的最后一次出现。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在可变 span 中查找任意两个指定值的最后一次出现。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 span 中查找来自序列的任意值的最后一次出现。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在可变 span 中查找来自序列的任意值的最后一次出现。 |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 在可变 span 中查找来自可变序列的任意值的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 在 span 中查找除指定的三个值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 在可变 span 中查找除指定的三个值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 span 中查找除指定的两个值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在可变 span 中查找除指定的两个值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 在 span 中查找除指定值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 在可变 span 中查找除指定值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在 span 中查找除序列中的值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 在可变 span 中查找除序列中的值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 在可变 span 中查找除可变序列中的值之外的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 span 中查找超出指定范围的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在可变 span 中查找超出指定范围的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 在 span 中查找位于指定范围内的任何元素的最后一次出现。 |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在可变 span 中查找位于指定范围内的任何元素的最后一次出现。 |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 确定两个 ReadOnlySpan 是否在内存中重叠（不计算偏移量）。 |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 确定 [Span](../system/span/) 和 [ReadOnlySpan](../system/readonlyspan/) 在内存中是否重叠（不计算偏移量）。 |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | 确定两个 ReadOnlySpan 是否在内存中重叠并计算偏移量。 |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | 确定 [Span](../system/span/) 和 [ReadOnlySpan](../system/readonlyspan/) 在内存中是否重叠并计算偏移量。 |
| void [Replace](./replace/)([Span](../system/span/)\<T\>\&, const T\&, const T\&) | 在 [Span](../system/span/) 中将所有出现的值替换为新值。 |
| void [Replace](./replace/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 从源复制元素到目标，在复制过程中替换指定的值。 |
| void [Reverse](./reverse/)([Span](../system/span/)\<T\>\&) | 就地反转 [Span](../system/span/) 中元素的顺序。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 对两个 ReadOnlySpan 进行字典序比较。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 对 [Span](../system/span/) 和 [ReadOnlySpan](../system/readonlyspan/) 进行字典序比较。 |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 对 [ReadOnlySpan](../system/readonlyspan/) 和 [Span](../system/span/) 进行字典序比较。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 确定两个 ReadOnlySpan 是否以相同顺序包含完全相同的元素。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 确定 [Span](../system/span/) 和 [ReadOnlySpan](../system/readonlyspan/) 是否以相同顺序包含完全相同的元素。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自定义比较器确定两个 ReadOnlySpan 是否包含相等的元素。 |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自定义比较器确定 [Span](../system/span/) 和 [ReadOnlySpan](../system/readonlyspan/) 是否包含相等的元素。 |
| void [Sort](./sort/)(const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自定义比较器对 [Span](../system/span/) 进行排序。 |
| void [Sort](./sort/)([Span](../system/span/)\<T\>\&) | 使用默认比较对 [Span](../system/span/) 进行排序。 |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 使用自定义比较器对键值对进行排序（键和值一起排序） |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, [System::Comparison](../system/comparison/)\<TKey\>) | 使用比较委托对键值对进行排序。 |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&) | 使用默认比较对键值对进行排序。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 检查 span 是否以指定值开始。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 检查 span 是否以指定的值 span 开始。 |
| **bool** [StartsWith](./startswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 检查可变 span 是否以指定的只读值 span 开始。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 检查只读 span 是否以指定的可变值 span 开始。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用字符串比较检查字符 span 是否以指定的值 span 开始。 |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<[String](../system/string/)\>\&, const char16_t *) | 检查字符串 span 是否以指定的字符数组开始。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, T) | 从有类型的 span 两端修剪指定元素。 |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, T) | 从可变有类型的 span 两端修剪指定元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 从有类型的 span 两端修剪指定元素。 |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 从可变有类型的 span 两端修剪指定元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 从字符 span 两端修剪空白字符。 |
| [Span](../system/span/)\<char16_t\> [Trim](./trim/)([Span](../system/span/)\<char16_t\>\&) | 从可变字符 span 两端修剪空白字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 从有类型的 span 开头修剪指定元素。 |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const T\&) | 从可变有类型的 span 开头修剪指定元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 从有类型的 span 开头修剪指定元素。 |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 从可变有类型的 span 开头修剪指定元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 从字符 span 末尾修剪空白字符。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&) | 从可变字符 span 末尾修剪空白字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | 从字符 span 末尾修剪指定字符。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, char16_t) | 从可变字符 span 末尾修剪指定字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 从字符 span 末尾修剪指定字符集。 |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 从可变字符 span 末尾修剪指定字符集。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 从有类型的 span 开头修剪指定元素。 |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const T\&) | 从可变有类型的 span 开头修剪指定元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 从有类型的 span 开头修剪指定元素。 |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 从可变有类型的 span 开头修剪指定元素。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 从字符 span 开头修剪空白字符。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&) | 从可变字符 span 开头修剪空白字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | 从字符 span 开头修剪指定字符。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, char16_t) | 从可变字符 span 开头修剪指定字符。 |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 从字符 span 开头修剪指定字符集。 |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 从可变字符 span 开头修剪指定字符集。 |
| **int32_t** [CompareTo](./compareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用指定的字符串比较规则比较两个字符 span。 |
| **bool** [Equals](./equals/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 使用 StringComparison 比较两个 ReadOnlySpan<char16_t> 是否相等。 |
| **bool** [IsWhiteSpace](./iswhitespace/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 检查整个 span 是否仅包含空白字符。 |
| **int32_t** [ToLower](./tolower/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | 使用指定文化将字符转换为小写。 |
| **int32_t** [ToLowerInvariant](./tolowerinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | 使用不变文化将字符转换为小写。 |
| **int32_t** [ToUpper](./toupper/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | 使用指定文化将字符转换为大写。 |
| **int32_t** [ToUpperInvariant](./toupperinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | 使用不变文化将字符转换为大写。 |