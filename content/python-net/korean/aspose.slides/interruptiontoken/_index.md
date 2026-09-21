---
title: InterruptionToken class
second_title: Aspose.Slides for Python용 .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/interruptiontoken/
---
## InterruptionToken 클래스

이 클래스는 중단이 요청되었는지 신호를 보내기 위해 장기 실행 작업에 사용할 토큰을 나타냅니다.

InterruptionToken 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`none`](/slides/python-net/ko/aspose.slides/interruptiontoken/none/) | 빈 중단 토큰을 나타냅니다.<br/>            이 토큰을 사용할 때 [`InterruptionTokenSource.interrupt`](/slides/python-net/ko/aspose.slides/interruptiontokensource/interrupt)를 통해 장기 실행 작업이 중단되지 않습니다. |
| [`is_interruption_requested`](/slides/python-net/ko/aspose.slides/interruptiontoken/is_interruption_requested/) | 반환 **bool**.true 중단이 요청된 경우. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/ko/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | 중단이 요청된 경우 OperationCanceledException을 발생시킵니다.<br/>            중단이 요청되었습니다. |

### 또 보기
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)