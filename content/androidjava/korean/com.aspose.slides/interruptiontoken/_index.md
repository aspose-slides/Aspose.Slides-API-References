---
title: InterruptionToken
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 이 클래스는 장시간 실행 작업에서 중단 요청 여부를 알리기 위해 사용할 토큰을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/interruptiontoken/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

이 클래스는 장시간 실행 작업에서 중단 요청 여부를 알리기 위해 사용할 토큰을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getNone()](#getNone--) | 빈 중단 토큰을 나타냅니다. |
| [isInterruptionRequested()](#isInterruptionRequested--) | 중단이 요청된 경우 true를 반환합니다. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 중단이 요청된 경우 예외를 발생시킵니다. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

빈 중단 토큰을 나타냅니다.

--------------------

이 토큰을 사용할 경우 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt)를 통해 장기 실행 작업이 중단되지 않습니다.

**반환:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

중단이 요청된 경우 true를 반환합니다.

**반환:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

중단이 요청된 경우 예외를 발생시킵니다.