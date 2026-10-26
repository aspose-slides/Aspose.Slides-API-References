---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다.
type: docs
weight: 53
url: /ko/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 디코드할 바이트. |
| count | int | 바이트 수. |

### 반환 값

문자 수.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코드할 바이트. |
| index | int | 슬라이스 시작 위치. |
| count | int | 슬라이스 크기. |

### 반환 값

문자 수.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코드할 바이트. |

### 반환 값

문자 수.

## ICUEncoding::GetCharCount(const uint8_t *, int) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 디코드할 바이트. |
| count | int | 바이트 수. |

### 반환 값

문자 수.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICUEncoding](../)
* 네임스페이스 [System::Text](../../)
* Library [Aspose.Slides](../../../)