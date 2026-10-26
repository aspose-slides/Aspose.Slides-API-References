---
title: BaseDictionary()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 빈 데이터 구조를 생성합니다.
type: docs
weight: 14
url: /ko/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() 생성자

빈 데이터 구조를 생성합니다.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) 생성자

기본 맵에 인수를 전달하기 위한 포워딩 생성자입니다.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Args | 맵에 전달할 인수의 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | int | 기본 맵에 전달할 인수. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) 생성자

복사 생성자.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Args | 맵 생성자 인수의 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) 로부터 데이터를 복사합니다. |
| args | const Args\&... | 기본 맵 생성자에 전달할 인수. |

## BaseDictionary::BaseDictionary(BaseType *) 생성자

복사 생성자.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) 로부터 데이터를 복사합니다. |

## 참고

* Typedef [BaseType](../basetype/)
* 클래스 [BaseDictionary](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)