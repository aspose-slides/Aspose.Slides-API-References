---
title: MakeSharedPtr()
second_title: Aspose.Slides for C++ API 참조
description: 원시 포인터를 스마트 포인터로 변환합니다.
type: docs
weight: 2900
url: /ko/system/makesharedptr/
---
## System::MakeSharedPtr(X *) 함수

원시 포인터를 스마트 포인터로 변환합니다.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 가리키는 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| p | X * | 객체에 대한 원시 포인터. |

### 반환 값

객체에 대한 공유 스마트 포인터.

## System::MakeSharedPtr(const X *) 함수

원시 포인터를 스마트 포인터로 변환합니다. const 포인터에 대한 오버로드입니다. C# 메서드가 const 로 번역될 때 ‘this’ 변수를 사용할 때 유용합니다.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 가리키는 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| p | const X * | 객체에 대한 원시 포인터. |

### 반환 값

객체에 대한 공유 스마트 포인터.

## 참조

* 클래스 [SmartPtr](../smartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)