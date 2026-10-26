---
title: TypeInfo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 생성자(형식이 설정되지 않음).
type: docs
weight: 40
url: /ko/system/typeinfo/typeinfo/
---
## TypeInfo::TypeInfo() 생성자

기본 생성자(형식이 설정되지 않음).

```cpp
System::TypeInfo::TypeInfo()
```

## TypeInfo::TypeInfo(std::nullptr_t) 생성자

null 객체 생성자(형식이 설정되지 않음).

```cpp
System::TypeInfo::TypeInfo(std::nullptr_t)
```

## TypeInfo::TypeInfo(const char_t *) 생성자

생성자.

```cpp
System::TypeInfo::TypeInfo(const char_t *name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const char_t * | 타입 이름. |

## TypeInfo::TypeInfo(const char_t *, uint32_t) 생성자

생성자.

```cpp
System::TypeInfo::TypeInfo(const char_t *name, uint32_t hash)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const char_t * | 타입 이름. |
| hash | **uint32_t** | 타입 이름 해시. |

## TypeInfo::TypeInfo(const std::type_info\&) 생성자

생성자.

```cpp
System::TypeInfo::TypeInfo(const std::type_info &info)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| info | const std::type_info\& | 타입에 대한 정보. |

## 참고

* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)