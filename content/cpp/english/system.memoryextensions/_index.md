---
title: "System::MemoryExtensions"
second_title: Aspose.Slides for C++ API Reference
description: Provides extension methods for memory operations on spans and arrays.
type: docs
weight: 612
url: /system.memoryextensions/
---

Provides extension methods for memory operations on spans and arrays.

## Functions

| Function | Description |
| --- | --- |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [AsSpan](./asspan/)(const [String](../system/string/)\&, **int32_t**, **int32_t**) | Creates a read-only span from a string. |
| [Span](../system/span/)\<T\> [AsSpan](./asspan/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, **int32_t**, **int32_t**) | Creates a span from an array. |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TComparable\&) | Performs binary search on a sorted span. |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Performs binary search on a sorted span using a custom comparer. |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const TComparable\&) | Performs binary search on a mutable sorted span. |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Performs binary search on a mutable sorted span using a custom comparer. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the length of the common prefix between two spans. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the length of the common prefix between a mutable span and a read-only span. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Finds the length of the common prefix between two mutable spans. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | Finds the length of the common prefix between two spans using a custom equality comparer. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | Finds the length of the common prefix between a mutable span and a read-only span using a custom equality comparer. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | Finds the length of the common prefix between two mutable spans using a custom equality comparer. |
| **int32_t** [CompareTo](./compareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Compares two character spans with specified string comparison rules. |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Checks if a character span contains another character span with specified comparison rules. |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Checks if a read-only span contains a specific value. |
| **bool** [Contains](./contains/)(const [Span](../system/span/)\<T\>\&, const T\&) | Checks if a mutable span contains a specific value. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Checks if a read-only span contains any of two values. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Checks if a read-only span contains any of three values. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Checks if a mutable span contains any of two values. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Checks if a mutable span contains any of three values. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Checks if a read-only span contains any value from another span. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Checks if a mutable span contains any value from a read-only span. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Checks if a read-only span contains any element except three specified values. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Checks if a mutable span contains any element except three specified values. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Checks if a read-only span contains any element except two specified values. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Checks if a mutable span contains any element except two specified values. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Checks if a read-only span contains any element except a specified value. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | Checks if a mutable span contains any element except a specified value. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Checks if a read-only span contains any element except those in another span. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Checks if a mutable span contains any element except those in a read-only span. |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Checks if a read-only span contains any element outside the specified range. |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Checks if a mutable span contains any element outside the specified range. |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Checks if a read-only span contains any element within the specified range. |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Checks if a mutable span contains any element within the specified range. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, [Span](../system/span/)\<T\>\&) | Copies elements from an array to a span. |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Counts occurrences of a value in a read-only span. |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Counts occurrences of a span within another read-only span. |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const T\&) | Counts occurrences of a single value in a Span<T> |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Counts occurrences of a ReadOnlySpan<T> in a Span<T> |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Determines if a ReadOnlySpan<char16_t> ends with the specified value using StringComparison. |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Determines if a ReadOnlySpan<T> ends with a single value. |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Determines if a ReadOnlySpan<T> ends with another ReadOnlySpan<T> |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Determines if a Span<T> ends with a ReadOnlySpan<T> |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Determines if a ReadOnlySpan<T> ends with a Span<T> |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Determines if a Span<T> ends with another Span<T> |
| **bool** [Equals](./equals/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Compares two ReadOnlySpan<char16_t> for equality using StringComparison. |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Finds the index of a ReadOnlySpan<char16_t> value in a ReadOnlySpan<char16_t> with StringComparison. |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the index of a ReadOnlySpan<T> value in another ReadOnlySpan<T> |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Finds the index of a single value in a ReadOnlySpan<T> |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the index of a ReadOnlySpan<T> value in a Span<T> |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | Finds the index of a single value in a Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Finds the index of the first occurrence of any of two specified values in a ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Finds the index of the first occurrence of any of three specified values in a ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Finds the index of the first occurrence of any of two specified values in a Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Finds the index of the first occurrence of any of three specified values in a Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the index of the first occurrence of any value from a span in another ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the index of the first occurrence of any value from a span in a Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Finds the index of the first element that is not equal to the specified value in a ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Finds the index of the first element that is not equal to either of two specified values in a ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Finds the index of the first element that is not equal to any of three specified values in a ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | Finds the index of the first element that is not equal to the specified value in a Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Finds the index of the first element that is not equal to either of two specified values in a Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Finds the index of the first element that is not equal to any of three specified values in a Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the index of the first element that is not equal to any value in a span of values. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the index of the first element that is not equal to any value in a span of values in a Span<T> |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Finds the index of the first element that is outside the specified range in a ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Finds the index of the first element that is outside the specified range in a Span<T> |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Finds the index of the first element that is within the specified range in a ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Finds the index of the first element that is within the specified range in a Span<T> |
| **bool** [IsWhiteSpace](./iswhitespace/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Checks if the entire span consists only of whitespace characters. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Finds the last occurrence of a value within a span using specified string comparison. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the last occurrence of a sequence within a span. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Finds the last occurrence of a single value within a span. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the last occurrence of a sequence within a mutable span. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | Finds the last occurrence of a single value within a mutable span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Finds the last occurrence of any of three specified values within a span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Finds the last occurrence of any of three specified values within a mutable span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Finds the last occurrence of any of two specified values within a span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Finds the last occurrence of any of two specified values within a mutable span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the last occurrence of any value from a sequence within a span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the last occurrence of any value from a sequence within a mutable span. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Finds the last occurrence of any value from a mutable sequence within a mutable span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Finds the last occurrence of any element except three specified values within a span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Finds the last occurrence of any element except three specified values within a mutable span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Finds the last occurrence of any element except two specified values within a span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Finds the last occurrence of any element except two specified values within a mutable span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Finds the last occurrence of any element except a specified value within a span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | Finds the last occurrence of any element except a specified value within a mutable span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the last occurrence of any element except values from a sequence within a span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Finds the last occurrence of any element except values from a sequence within a mutable span. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Finds the last occurrence of any element except values from a mutable sequence within a mutable span. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Finds the last occurrence of any element outside the specified range within a span. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Finds the last occurrence of any element outside the specified range within a mutable span. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Finds the last occurrence of any element within the specified range within a span. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Finds the last occurrence of any element within the specified range within a mutable span. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Determines if two ReadOnlySpans overlap in memory without calculating offset. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Determines if a [Span](../system/span/) and [ReadOnlySpan](../system/readonlyspan/) overlap in memory without calculating offset. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | Determines if two ReadOnlySpans overlap in memory and calculates the offset. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | Determines if a [Span](../system/span/) and [ReadOnlySpan](../system/readonlyspan/) overlap in memory and calculates the offset. |
| void [Replace](./replace/)([Span](../system/span/)\<T\>\&, const T\&, const T\&) | Replaces all occurrences of a value with a new value in a [Span](../system/span/). |
| void [Replace](./replace/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Copies elements from source to destination, replacing specified values during copy. |
| void [Reverse](./reverse/)([Span](../system/span/)\<T\>\&) | Reverses the order of elements in a [Span](../system/span/) in-place. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Compares two ReadOnlySpans lexicographically. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Compares a [Span](../system/span/) and [ReadOnlySpan](../system/readonlyspan/) lexicographically. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Compares a [ReadOnlySpan](../system/readonlyspan/) and [Span](../system/span/) lexicographically. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Determines if two ReadOnlySpans contain identical elements in the same order. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Determines if a [Span](../system/span/) and [ReadOnlySpan](../system/readonlyspan/) contain identical elements in the same order. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Determines if two ReadOnlySpans contain equal elements using a custom comparer. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Determines if a [Span](../system/span/) and [ReadOnlySpan](../system/readonlyspan/) contain equal elements using a custom comparer. |
| void [Sort](./sort/)(const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Sorts a [Span](../system/span/) using a custom comparer. |
| void [Sort](./sort/)([Span](../system/span/)\<T\>\&) | Sorts a [Span](../system/span/) using default comparison. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Sorts key-value pairs using a custom comparer (keys and values sorted together) |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, [System::Comparison](../system/comparison/)\<TKey\>) | Sorts key-value pairs using a comparison delegate. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&) | Sorts key-value pairs using default comparison. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Checks if the span starts with the specified value. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<[String](../system/string/)\>\&, const char16_t *) | Checks if a string span starts with the specified character array. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Checks if the span starts with the specified value span. |
| **bool** [StartsWith](./startswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Checks if the mutable span starts with the specified read-only value span. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Checks if the read-only span starts with the specified mutable value span. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Checks if the character span starts with the specified value span using string comparison. |
| **int32_t** [ToLower](./tolower/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | Converts characters to lowercase using specified culture. |
| **int32_t** [ToLowerInvariant](./tolowerinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | Converts characters to lowercase using invariant culture. |
| **int32_t** [ToUpper](./toupper/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | Converts characters to uppercase using specified culture. |
| **int32_t** [ToUpperInvariant](./toupperinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | Converts characters to uppercase using invariant culture. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, T) | Trims specified element from both ends of a typed span. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, T) | Trims specified element from both ends of a mutable typed span. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Trims specified elements from both ends of a typed span. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Trims specified elements from both ends of a mutable typed span. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Trims whitespace characters from both ends of a character span. |
| [Span](../system/span/)\<char16_t\> [Trim](./trim/)([Span](../system/span/)\<char16_t\>\&) | Trims whitespace characters from both ends of a mutable character span. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Trims specified element from the end of a typed span. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const T\&) | Trims specified element from the end of a mutable typed span. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Trims specified elements from the end of a typed span. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Trims specified elements from the end of a mutable typed span. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Trims whitespace characters from the end of a character span. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&) | Trims whitespace characters from the end of a mutable character span. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | Trims specified character from the end of a character span. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, char16_t) | Trims specified character from the end of a mutable character span. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Trims specified characters from the end of a character span. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Trims specified characters from the end of a mutable character span. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Trims specified element from the start of a typed span. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const T\&) | Trims specified element from the start of a mutable typed span. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Trims specified elements from the start of a typed span. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Trims specified elements from the start of a mutable typed span. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Trims whitespace characters from the start of a character span. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&) | Trims whitespace characters from the start of a mutable character span. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | Trims specified character from the start of a character span. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, char16_t) | Trims specified character from the start of a mutable character span. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Trims specified characters from the start of a character span. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Trims specified characters from the start of a mutable character span. |
