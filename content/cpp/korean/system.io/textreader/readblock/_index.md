---
title: ReadBlock()
second_title: Aspose.Slides for C++ API 참조
description: 현재 텍스트 리더에서 지정된 최대 문자 수를 읽고, 지정된 인덱스부터 버퍼에 데이터를 씁니다.
type: docs
weight: 53
url: /ko/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) 메서드

현재 텍스트 리더에서 지정된 최대 문자 수를 읽고, 지정된 인덱스부터 버퍼에 데이터를 씁니다.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 읽은 데이터를 쓸 문자 버퍼 |
| index | int | **buffer**에 쓰기를 시작할 0 기반 인덱스 |
| count | int | 읽을 최대 문자 수 |

### 반환 값

읽은 실제 문자 수

## 또 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)