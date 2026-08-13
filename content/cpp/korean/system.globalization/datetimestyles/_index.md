---
title: DateTimeStyles
second_title: Aspose.Slides for C++ API 참조
description: 날짜 및 시간 형식 옵션을 정의합니다. 비트 플래그.
type: docs
weight: 456
url: /ko/system.globalization/datetimestyles/
---
## DateTimeStyles 열거형

날짜와 시간 형식 옵션을 정의합니다. 비트 플래그.

```cpp
enum class DateTimeStyles : int32_t
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 기본값. |
| AllowLeadingWhite | 1 | 앞쪽 공백을 무시합니다. |
| AllowTrailingWhite | 2 | 뒤쪽 공백을 무시합니다. |
| AllowInnerWhite | 4 | 내부 공백을 무시합니다. |
| AllowWhiteSpaces | n/a | 모든 공백을 무시합니다. |
| NoCurrentDateDefault | 8 | 날짜/시간 문자열을 구문 분석할 때 연도/월/일이 모두 없으면 현재 연도/월/일 대신 기본 날짜를 0001/1/1로 설정합니다. |
| AdjustToUniversal | 16 | 날짜/시간 문자열을 구문 분석할 때 시간대 지정자("GMT","Z","+xxxx","-xxxx")가 있으면 파싱된 시간을 GMT 기준으로 조정합니다. |
| AssumeLocal | 32 | 시간대가 지정되지 않으면 로컬 시간대를 사용합니다. |
| AssumeUniversal | 64 | 시간대가 지정되지 않으면 UTC를 사용합니다. |
| RoundtripKind | 128 | 입력이 지정되지 않음, 로컬 또는 UTC인지를 유지하려 시도합니다. |

## 참고

* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)