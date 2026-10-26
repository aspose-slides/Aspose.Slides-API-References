---
title: IsSurrogatePair()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 지정된 문자가 UTF-16 서러게이트 페어인지 여부를 결정합니다.
type: docs
weight: 27
url: /ko/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) 메서드


두 지정된 문자가 UTF-16 서러게이트 페어인지 여부를 결정합니다.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | 높은 서러게이트인지 검사되는 문자 |
| lowSurrogate | char_t | 낮은 서러게이트인지 검사되는 문자 |

### Return Value

지정된 문자가 서러게이트 페어를 형성하면 true, 그렇지 않으면 false

## Char::IsSurrogatePair(const String\&, int) 메서드


지정된 문자 버퍼에서 연속된 두 문자가 서러게이트 페어인지 여부를 결정합니다.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | 문자열 |
| index | int | 지정된 버퍼에서 테스트할 문자 시퀀스가 시작되는 0 기반 인덱스 |

### Return Value

지정된 문자가 서러게이트 페어를 형성하면 true, 그렇지 않으면 false

## See Also

* Class [Char](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)