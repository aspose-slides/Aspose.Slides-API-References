---
title: Handle()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 각 내부 예외에 대해 핸들러 함수를 호출하고 처리되지 않은 예외를 다시 발생시킵니다.
type: docs
weight: 66
url: /ko/system/details_aggregateexception/handle/
---
## 세부 정보_AggregateException::Handle(const Func\<Exception, bool\>\&) 메서드

각 내부 예외에 대해 핸들러 함수를 호출하고 처리되지 않은 예외를 다시 발생시킵니다.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Exception을 받아 처리되면 true를 반환하는 함수입니다. |

## 비고

모든 예외가 처리되면 메서드는 정상적으로 반환됩니다; 그렇지 않으면 처리되지 않은 예외를 포함하는 새로운 AggregateException이 발생합니다.

## 참고

* Typedef [Exception](../../exception/)
* 클래스 [Func](../../func/)
* 클래스 [Details_AggregateException](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)