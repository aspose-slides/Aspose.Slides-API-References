---
title: MulticastDelegate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비어 있는 컬렉션을 생성합니다.
type: docs
weight: 1
url: /ko/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() method

비어 있는 컬렉션을 생성합니다.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) method

기본 생성자와 동일합니다.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) method

델리게이트 컬렉션의 얕은 복사를 수행합니다.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | const MulticastDelegate\& | 델리게이트 컬렉션을 복사할 MulticastDelegate 클래스의 인스턴스. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) method

이동 생성자.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | MulticastDelegate\&& | 델리게이트 컬렉션을 이동할 MulticastDelegate 클래스의 인스턴스. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) method

인스턴스를 생성하고 지정된 델리게이트를 델리게이트 컬렉션에 추가합니다.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | 델리게이트 컬렉션에 추가할 델리게이트 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) method

인스턴스를 생성하고 지정된 값을 델리게이트 컬렉션에 추가합니다.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 새로 구성된 인스턴스의 델리게이트 컬렉션에 추가할 값의 유형; 해당 유형은 Callback 유형으로 변환 가능해야 합니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg | T | 델리게이트 컬렉션에 추가할 값 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) method

인스턴스를 생성하고 지정된 값을 델리게이트 컬렉션에 추가합니다.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | 델리게이트 컬렉션에 추가할 값 |

## 참조

* 타입 정의 [Callback](../callback/)
* 클래스 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)