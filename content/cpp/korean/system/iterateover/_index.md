---
title: IterateOver()
second_title: Aspose.Slides for C++ API 참조
description: "이 함수는 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프와 함께 사용할 수 있게 합니다. begin(), end() 메서드가 없는 Enumerable에 대한 이 오버로드는 대상 유형 인수를 사용하여 (auto& value : IterateOver<SomeType>(enumerable))와 같이 사용합니다."
type: docs
weight: 2471
url: /ko/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) 함수

이 함수는 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프와 함께 사용할 수 있도록 합니다. begin(), end() 메서드가 없는 Enumerable에 대한 이 오버로드는 대상 유형 인수를 사용하여 (auto& value : IterateOver<SomeType>(enumerable))와 같이 사용합니다.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 유형으로, iterator에서 반환되어야 합니다. |
| Enumerable | 래핑된 객체의 유형 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 함수

이 함수는 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프와 함께 사용할 수 있도록 합니다. 기본 대상 유형을 사용하는 Enumerable에 대한 이 오버로드는 (auto& value : IterateOver(enumerable))와 같이 사용되며, 다음 C# 코드와 유사합니다. foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Enumerable | 래핑된 객체의 유형 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 함수

이 함수는 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프와 함께 사용할 수 있도록 합니다. begin(), end() 메서드가 있는 Enumerable에 대한 이 오버로드는 기본 대상 유형을 사용하여 (auto& value : IterateOver(enumerable))와 같이 사용합니다.

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Enumerable | 래핑된 객체의 유형 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 함수

이 함수는 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프와 함께 사용할 수 있도록 합니다. begin(), end() 메서드가 있는 Enumerable에 대한 이 오버로드는 대상 유형이 iterator의 원래 value_type과 동일합니다.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Enumerable | 래핑된 객체의 유형 |
| T | iterator에서 반환되어야 하는 대상 유형 |

## System::IterateOver(System::SmartPtr\<Enumerable\>) 함수

이 함수는 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프와 함께 사용할 수 있도록 합니다. begin(), end() 메서드가 있는 Enumerable에 대한 이 오버로드는 대상 유형이 iterator의 원래 value_type과 다릅니다.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Enumerable | 래핑된 객체의 유형 |
| T | iterator에서 반환되어야 하는 대상 유형 |

## System::IterateOver(const Enumerable *) 함수

이 함수는 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프와 함께 사용할 수 있도록 합니다. 기본 대상 유형을 사용하는 Enumerable에 대한 이 오버로드입니다.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Enumerable | 래핑된 객체의 유형 |

## System::IterateOver(const Enumerable *) 함수

이 함수는 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프와 함께 사용할 수 있도록 합니다. begin(), end() 메서드가 없는 Enumerable에 대한 이 오버로드는 대상 유형 인수를 사용하여 (auto& value : IterateOver<SomeType>(enumerable))와 같이 사용합니다.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 유형으로, iterator에서 반환되어야 합니다. |
| Enumerable | 래핑된 객체의 유형 |

## 참고

* 클래스 [SmartPtr](../smartptr/)
* 구조체 [IsSmartPtr](../issmartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)