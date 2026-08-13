---
title: AsCast()
second_title: Aspose.Slides for C++ API 참조
description: 소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 간단한 생성자와 같은 캐스트가 필요할 때 사용됩니다.
type: docs
weight: 2640
url: /ko/system/ascast/
---
## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 간단한 생성자와 같은 캐스트가 필요할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 소스와 결과 유형이 동일할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 예외 래퍼에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 객체를 예외로 캐스트할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 소스와 결과가 모두 스마트 포인터일 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과. 변환이 없을 경우 nullptr를 반환합니다.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 소스와 결과가 모두 스마트 포인터이며 결과 유형에 명시적인 SmartPtr<...>가 포함될 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과. 변환이 없을 경우 nullptr를 반환합니다.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 객체를 nullable로 언박싱할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과. 변환이 없을 경우 빈 nullable를 반환합니다.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 객체가 아닌 유형으로의 잘못된 언박싱입니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

항상 null을 반환합니다.

## System::AsCast(const Source\&) 함수

객체가 아닌 유형으로의 잘못된 언박싱입니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

항상 null을 반환합니다.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. nullable 객체를 박싱할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 일반 객체를 박싱할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 일반 객체를 박싱할 때 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 문자열 언박싱에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. nullptr 캐스팅에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과.

## System::AsCast(const Source\&) 함수

소스 유형을 'as' 연산자 캐스트를 사용하여 결과 유형으로 변환합니다. 배열 간 캐스팅에 사용됩니다.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/)를 캐스트합니다. |

### 반환값

캐스트 결과. 배열 요소 중 변환이 가능한 것이 없을 경우 nullptr를 반환합니다.

## 참고

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)