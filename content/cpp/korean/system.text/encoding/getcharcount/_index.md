---
title: GetCharCount()
second_title: Aspose.Slides C++ API 레퍼런스
description: 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.
type: docs
weight: 261
url: /ko/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트. |
| index | int | 슬라이스 시작 위치. |
| count | int | 슬라이스 크기. |

### 반환 값

문자 수.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) method

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트. |

### 반환 값

문자 수.

## Encoding::GetCharCount(const uint8_t *, int) method

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 디코딩할 바이트. |
| count | int | 바이트 수. |

### 반환 값

문자 수.

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)