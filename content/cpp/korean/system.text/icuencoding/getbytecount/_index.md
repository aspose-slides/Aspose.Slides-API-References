---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다.
type: docs
weight: 27
url: /ko/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) 메서드

문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | const char_t * | 문자 버퍼. |
| count | int | [Buffer](../../../system/buffer/) 크기. |

### 반환값

필요한 버퍼 크기.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) 메서드

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) 메서드

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) 메서드

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) 메서드

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) 메서드

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) 메서드

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## 참조

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICUEncoding](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)