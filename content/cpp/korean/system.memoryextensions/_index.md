---
title: "System::MemoryExtensions"
second_title: "Aspose.Slides for C++ API 레퍼런스"
description: "스팬 및 배열에 대한 메모리 작업을 위한 확장 메서드를 제공합니다."
type: docs
weight: 625
url: /ko/system.memoryextensions/
---
span 및 배열에 대한 메모리 작업을 위한 확장 메서드를 제공합니다.

## 함수

| 함수 | 설명 |
| --- | --- |
| [Span](../system/span/)\<T\> [AsSpan](./asspan/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, **int32_t**, **int32_t**) | 배열에서 span을 생성합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [AsSpan](./asspan/)(const [String](../system/string/)\&, **int32_t**, **int32_t**) | 문자열에서 읽기 전용 span을 생성합니다. |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TComparable\&) | 정렬된 span에서 이진 검색을 수행합니다. |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 정렬된 span에서 사용자 지정 비교자를 사용하여 이진 검색을 수행합니다. |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const TComparable\&) | 가변 정렬된 span에서 이진 검색을 수행합니다. |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 가변 정렬된 span에서 사용자 지정 비교자를 사용하여 이진 검색을 수행합니다. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 두 span 사이의 공통 접두사의 길이를 찾습니다. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 span과 읽기 전용 span 사이의 공통 접두사의 길이를 찾습니다. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 두 가변 span 사이의 공통 접두사의 길이를 찾습니다. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 두 span 사이의 공통 접두사의 길이를 사용자 지정 등가 비교자를 사용하여 찾습니다. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 가변 span과 읽기 전용 span 사이의 공통 접두사의 길이를 사용자 지정 등가 비교자를 사용하여 찾습니다. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | 두 가변 span 사이의 공통 접두사의 길이를 사용자 지정 등가 비교자를 사용하여 찾습니다. |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 읽기 전용 span에 특정 값이 포함되어 있는지 확인합니다. |
| **bool** [Contains](./contains/)(const [Span](../system/span/)\<T\>\&, const T\&) | 가변 span에 특정 값이 포함되어 있는지 확인합니다. |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 문자 span이 지정된 비교 규칙을 사용하여 다른 문자 span을 포함하는지 확인합니다. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 읽기 전용 span에 두 값 중 하나가 포함되는지 확인합니다. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 읽기 전용 span에 세 값 중 하나가 포함되는지 확인합니다. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 가변 span에 두 값 중 하나가 포함되는지 확인합니다. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 가변 span에 세 값 중 하나가 포함되는지 확인합니다. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 읽기 전용 span에 다른 span의 값이 포함되는지 확인합니다. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 span에 읽기 전용 span의 값이 포함되는지 확인합니다. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 읽기 전용 span에 지정된 세 값을 제외한 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 가변 span에 지정된 세 값을 제외한 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 읽기 전용 span에 지정된 두 값을 제외한 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 가변 span에 지정된 두 값을 제외한 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 읽기 전용 span에 지정된 값을 제외한 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 가변 span에 지정된 값을 제외한 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 읽기 전용 span에 다른 span의 요소를 제외한 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 span에 읽기 전용 span의 요소를 제외한 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 읽기 전용 span에 지정된 범위를 벗어나는 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 가변 span에 지정된 범위를 벗어나는 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 읽기 전용 span에 지정된 범위 내의 요소가 포함되는지 확인합니다. |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 가변 span에 지정된 범위 내의 요소가 포함되는지 확인합니다. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, [Span](../system/span/)\<T\>\&) | 배열에서 span으로 요소를 복사합니다. |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 읽기 전용 span에서 값이 나타나는 횟수를 셉니다. |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 다른 읽기 전용 span 내에서 span이 나타나는 횟수를 셉니다. |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const T\&) | Span<T>에서 단일 값이 나타나는 횟수를 셉니다. |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T>에서 ReadOnlySpan<T>가 나타나는 횟수를 셉니다. |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ReadOnlySpan<T>가 단일 값으로 끝나는지 판단합니다. |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ReadOnlySpan<T>가 다른 ReadOnlySpan<T>로 끝나는지 판단합니다. |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T>가 ReadOnlySpan<T>로 끝나는지 판단합니다. |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | ReadOnlySpan<T>가 Span<T>로 끝나는지 판단합니다. |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Span<T>가 다른 Span<T>로 끝나는지 판단합니다. |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | StringComparison을 사용하여 ReadOnlySpan<char16_t>가 지정된 값으로 끝나는지 판단합니다. |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 다른 ReadOnlySpan<T>에서 ReadOnlySpan<T> 값의 인덱스를 찾습니다. |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ReadOnlySpan<T>에서 단일 값의 인덱스를 찾습니다. |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T>에서 ReadOnlySpan<T> 값의 인덱스를 찾습니다. |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | Span<T>에서 단일 값의 인덱스를 찾습니다. |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | StringComparison을 사용하여 ReadOnlySpan<char16_t>에서 값의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ReadOnlySpan<T>에서 지정된 두 값 중 첫 번째 발생 위치의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ReadOnlySpan<T>에서 지정된 세 값 중 첫 번째 발생 위치의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Span<T>에서 지정된 두 값 중 첫 번째 발생 위치의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Span<T>에서 지정된 세 값 중 첫 번째 발생 위치의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 다른 ReadOnlySpan<T>에서 span의 값 중 첫 번째 발생 위치의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T>에서 span의 값 중 첫 번째 발생 위치의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ReadOnlySpan<T>에서 지정된 값과 같지 않은 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ReadOnlySpan<T>에서 지정된 두 값 중 어느 것과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ReadOnlySpan<T>에서 지정된 세 값 중 어느 것과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | Span<T>에서 지정된 값과 같지 않은 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Span<T>에서 지정된 두 값 중 어느 것과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Span<T>에서 지정된 세 값 중 어느 것과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 값의 span에서 어느 값과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Span<T>에서 값의 span 중 어느 값과도 같지 않은 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ReadOnlySpan<T>에서 지정된 범위를 벗어나는 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Span<T>에서 지정된 범위를 벗어나는 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ReadOnlySpan<T>에서 지정된 범위 내의 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Span<T>에서 지정된 범위 내의 첫 번째 요소의 인덱스를 찾습니다. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | span 내에서 시퀀스의 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | span 내에서 단일 값의 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 span 내에서 시퀀스의 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | 가변 span 내에서 단일 값의 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 지정된 문자열 비교를 사용하여 span 내에서 값의 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | span 내에서 지정된 세 값 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 가변 span 내에서 지정된 세 값 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | span 내에서 지정된 두 값 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 가변 span 내에서 지정된 두 값 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | span 내에서 시퀀스의 값 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 span 내에서 시퀀스의 값 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 가변 span 내에서 가변 시퀀스의 값 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | 스팬 내에서 지정된 세 값 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | 가변 스팬 내에서 지정된 세 값 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 스팬 내에서 지정된 두 값 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 가변 스팬 내에서 지정된 두 값 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 스팬 내에서 지정된 값을 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | 가변 스팬 내에서 지정된 값을 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 스팬 내에서 시퀀스의 값들을 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 스팬 내에서 시퀀스의 값들을 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 가변 스팬 내에서 가변 시퀀스의 값들을 제외한 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 스팬 내에서 지정된 범위 밖의 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 가변 스팬 내에서 지정된 범위 밖의 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | 스팬 내에서 지정된 범위 내의 모든 요소 중 마지막 발생을 찾습니다. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 가변 스팬 내에서 지정된 범위 내의 모든 요소 중 마지막 발생을 찾습니다. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 두 ReadOnlySpan이 메모리에서 오프셋을 계산하지 않고 겹치는지 확인합니다. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 메모리에서 오프셋을 계산하지 않고 [Span](../system/span/)와 [ReadOnlySpan](../system/readonlyspan/)가 겹치는지 확인합니다. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | 두 ReadOnlySpan이 메모리에서 겹치는지 확인하고 오프셋을 계산합니다. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | 메모리에서 [Span](../system/span/)와 [ReadOnlySpan](../system/readonlyspan/)가 겹치는지 확인하고 오프셋을 계산합니다. |
| void [Replace](./replace/)([Span](../system/span/)\<T\>\&, const T\&, const T\&) | [Span](../system/span/)에서 값의 모든 발생을 새 값으로 교체합니다. |
| void [Replace](./replace/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [Span](../system/span/)\<T\>\&, const T\&, const T\&) | 원본에서 대상으로 요소를 복사하면서, 지정된 값을 복사 중에 교체합니다. |
| void [Reverse](./reverse/)([Span](../system/span/)\<T\>\&) | [Span](../system/span/) 내 요소의 순서를 제자리에서 반전시킵니다. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 두 ReadOnlySpan을 사전식으로 비교합니다. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | [Span](../system/span/)와 [ReadOnlySpan](../system/readonlyspan/)를 사전식으로 비교합니다. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | [ReadOnlySpan](../system/readonlyspan/)와 [Span](../system/span/)를 사전식으로 비교합니다. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 두 ReadOnlySpan이 동일한 순서의 동일한 요소를 포함하는지 확인합니다. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | [Span](../system/span/)와 [ReadOnlySpan](../system/readonlyspan/)가 동일한 순서의 동일한 요소를 포함하는지 확인합니다. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 두 ReadOnlySpan이 사용자 지정 comparer를 사용하여 동일한 요소를 포함하는지 확인합니다. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | [Span](../system/span/)와 [ReadOnlySpan](../system/readonlyspan/)가 사용자 지정 comparer를 사용하여 동일한 요소를 포함하는지 확인합니다. |
| void [Sort](./sort/)(const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 사용자 지정 comparer를 사용하여 [Span](../system/span/)를 정렬합니다. |
| void [Sort](./sort/)([Span](../system/span/)\<T\>\&) | 기본 비교를 사용하여 [Span](../system/span/)를 정렬합니다. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | 키와 값을 함께 정렬하는 사용자 지정 comparer를 사용하여 키-값 쌍을 정렬합니다. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, [System::Comparison](../system/comparison/)\<TKey\>) | 비교 대리자를 사용하여 키-값 쌍을 정렬합니다. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&) | 기본 비교를 사용하여 키-값 쌍을 정렬합니다. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 스팬이 지정된 값으로 시작하는지 확인합니다. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 스팬이 지정된 값 스팬으로 시작하는지 확인합니다. |
| **bool** [StartsWith](./startswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 스팬이 지정된 읽기 전용 값 스팬으로 시작하는지 확인합니다. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | 읽기 전용 스팬이 지정된 가변 값 스팬으로 시작하는지 확인합니다. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 문자열 비교를 사용하여 문자 스팬이 지정된 값 스팬으로 시작하는지 확인합니다. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<[String](../system/string/)\>\&, const char16_t *) | 문자열 스팬이 지정된 문자 배열로 시작하는지 확인합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, T) | 타입된 스팬의 양쪽 끝에서 지정된 요소를 제거합니다. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, T) | 가변 타입된 스팬의 양쪽 끝에서 지정된 요소를 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 타입된 스팬의 양쪽 끝에서 지정된 요소들을 제거합니다. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 타입된 스팬의 양쪽 끝에서 지정된 요소들을 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 문자 스팬의 양쪽 끝에서 공백 문자를 제거합니다. |
| [Span](../system/span/)\<char16_t\> [Trim](./trim/)([Span](../system/span/)\<char16_t\>\&) | 가변 문자 스팬의 양쪽 끝에서 공백 문자를 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 타입된 스팬의 끝에서 지정된 요소를 제거합니다. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const T\&) | 가변 타입된 스팬의 끝에서 지정된 요소를 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 타입된 스팬의 끝에서 지정된 요소들을 제거합니다. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 타입된 스팬의 끝에서 지정된 요소들을 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 문자 스팬의 끝에서 공백 문자를 제거합니다. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&) | 가변 문자 스팬의 끝에서 공백 문자를 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | 문자 스팬의 끝에서 지정된 문자를 제거합니다. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, char16_t) | 가변 문자 스팬의 끝에서 지정된 문자를 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 문자 스팬의 끝에서 지정된 문자들을 제거합니다. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 가변 문자 스팬의 끝에서 지정된 문자들을 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | 타입된 스팬의 시작에서 지정된 요소를 제거합니다. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const T\&) | 가변 타입된 스팬의 시작에서 지정된 요소를 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 타입된 스팬의 시작에서 지정된 요소들을 제거합니다. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | 가변 타입된 스팬의 시작에서 지정된 요소들을 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 문자 스팬의 시작에서 공백 문자를 제거합니다. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&) | 가변 문자 스팬의 시작에서 공백 문자를 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | 문자 스팬의 시작에서 지정된 문자를 제거합니다. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, char16_t) | 가변 문자 스팬의 시작에서 지정된 문자를 제거합니다. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 문자 스팬의 시작에서 지정된 문자들을 제거합니다. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 가변 문자 스팬의 시작에서 지정된 문자들을 제거합니다. |
| **int32_t** [CompareTo](./compareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | 지정된 문자열 비교 규칙으로 두 문자 스팬을 비교합니다. |
| **bool** [Equals](./equals/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | StringComparison을 사용하여 두 ReadOnlySpan<char16_t>를 동일성으로 비교합니다. |
| **bool** [IsWhiteSpace](./iswhitespace/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | 스팬 전체가 공백 문자만으로 구성되어 있는지 확인합니다. |
| **int32_t** [ToLower](./tolower/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | 지정된 문화권을 사용하여 문자를 소문자로 변환합니다. |
| **int32_t** [ToLowerInvariant](./tolowerinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | 불변 문화권을 사용하여 문자를 소문자로 변환합니다. |
| **int32_t** [ToUpper](./toupper/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | 지정된 문화권을 사용하여 문자를 대문자로 변환합니다. |
| **int32_t** [ToUpperInvariant](./toupperinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | 불변 문화권을 사용하여 문자를 대문자로 변환합니다. |