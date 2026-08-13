---
title: ExplicitCast()
second_title: Aspose.Slides for C++ API 참조
description: 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 소스와 결과 유형이 동일할 때 사용됩니다.
type: docs
weight: 2627
url: /ko/system/explicitcast/
---
## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 소스와 결과 유형이 동일할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 간단한 생성자와 같은 캐스트가 필요할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 예외 래퍼에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 객체를 예외로 캐스팅할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 소스와 결과가 스마트 포인터이며 결과 타입에 명시적 SmartPtr<…>가 없을 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(Source) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 원시 포인터를 스마트 포인터로 캐스팅할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | Source | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 소스와 결과가 스마트 포인터이며 결과 타입에 명시적 SmartPtr<…>가 있을 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 널러블 객체를 언박싱할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 널러블을 박싱할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 널러블 객체를 언박싱할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. enum을 박싱할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 값 유형을 힙에 복사하고 스마트 포인터로 참조해야 할 때 사용됩니다(제네릭에서 인터페이스 타입으로 제한하지만 구조체 구현을 특수화).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 값 유형에서 인터페이스를 얻을 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 일반적인 박싱에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. [System::String](../string/) 박싱에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 인터페이스 언박싱에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 일반적인 언박싱에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. nullptr 캐스팅에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## System::ExplicitCast(const Source&) 함수


소스 유형을 결과 유형으로 명시적 캐스트를 사용하여 변환합니다. 배열 간 캐스팅에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 캐스팅할 값. |

### 반환 값

The cast result.

## 참조

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)