---
title: CompareOptions
second_title: Aspose.Slides for C++ API 참조
description: 문자열 비교 옵션.
type: docs
weight: 430
url: /ko/system.globalization/compareoptions/
---
## CompareOptions 열거형

[String](../../system/string/) 비교 옵션.

```cpp
enum class CompareOptions : int32_t
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 특별한 옵션이 없습니다. |
| IgnoreCase | 1 | 대소문자를 무시합니다. |
| IgnoreNonSpace | 2 | 비간격 결합 문자를 무시합니다. 예: 분음 부호. |
| IgnoreSymbols | 4 | 공백, 구두점 및 기타 문자들을 포함합니다. |
| IgnoreKanaType | 8 | 카나 종류를 무시합니다 (일본어). |
| IgnoreWidth | 16 | 문자열을 비교할 때 문자 너비를 무시합니다. |
| OrdinalIgnoreCase | 268435456 | 대소문자 차이를 무시한 순서 비교. |
| StringSort | 536870912 | 문자 비교에 문자열 정렬 알고리즘을 사용합니다. |
| Ordinal | 1073741824 | 첫 번째 비교에서 UTF 코드를 직접 비교합니다. |

## 참고

* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)