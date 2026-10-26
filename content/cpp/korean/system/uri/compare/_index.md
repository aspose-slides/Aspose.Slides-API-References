---
title: Compare()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 Uri 객체를 지정된 비교 규칙을 사용하여 비교합니다.
type: docs
weight: 521
url: /ko/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) 메서드

지정된 [Uri](../) 객체를 지정된 비교 규칙을 사용하여 비교합니다.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 첫 번째 비교 대상 |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 두 번째 비교 대상 |
| partsToCompare | [UriComponents](../../uricomponents/) | **uri1**와 **uri2**를 비교할 부분을 지정합니다 |
| compareFormat | [UriFormat](../../uriformat/) | URI 구성 요소를 비교할 때 사용되는 문자 이스케이프 방식을 지정합니다 |
| comparisonType | [StringComparison](../../stringcomparison/) | StringComparison 값 중 하나 |

### 반환 값

음수 값은 **uri1**이 **uri2**보다 작을 때, 0은 uri1과 uri2가 같을 때, 양수 값은 **uri1**이 **uri2**보다 클 때 반환됩니다.

## 관련 항목

* 열거형 [UriComponents](../../uricomponents/)
* 열거형 [UriFormat](../../uriformat/)
* 열거형 [StringComparison](../../stringcomparison/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [Uri](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)