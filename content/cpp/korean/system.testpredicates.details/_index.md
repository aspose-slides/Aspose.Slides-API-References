---
title: "System::TestPredicates::Details"
second_title: "Aspose.Slides C++ API 레퍼런스"
description: 
type: docs
weight: 937
url: /ko/system.testpredicates.details/
---
## 함수

| 함수 | 설명 |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | 적절한 직렬 변환 함수를 선택하여 객체를 문자열로 출력합니다. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | 요소를 (최대 32개) 출력하여 ICollection 스타일 컨테이너를 문자열로 변환합니다. |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | nullptr를 문자열로 출력합니다. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | [IEnumerable<bool>](../system.collections.generic/ienumerable/) 컬렉션을 요소를 (최대 32개) 출력하여 문자열로 변환합니다. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | [System::Object](../system/object/) 서브클래스를 ToString() 메서드를 사용하여 문자열로 출력합니다. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | [System::Object](../system/object/) 서브클래스를 ToString() 메서드를 사용하여 문자열로 출력합니다. |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 객체를 ToString() 메서드를 사용하여 문자열로 출력합니다. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 객체를 PrintTo 메서드를 사용하여 문자열로 출력합니다. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 객체를 PrintTo 메서드를 사용하여 문자열로 출력합니다. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | 쌍을 문자열로 출력합니다. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | 쌍을 문자열로 출력합니다. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 요소를 (최대 32개) 출력하여 STL 스타일 컨테이너를 문자열로 변환합니다. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | gtest에서 제공하는 함수를 사용하여 다른 유형을 문자열로 출력합니다. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | 출력을 위해 == 단언 실패를 형식화합니다. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | 출력을 위해 != 단언 실패를 형식화합니다. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | 출력을 위해 'same' 단언 실패를 형식화합니다. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | 출력을 위해 'not same' 단언 실패를 형식화합니다. |