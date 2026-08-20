---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: 이 클래스는 장기 실행 작업에서 중단이 요청되었는지 신호를 보내기 위해 사용할 토큰을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

이 클래스는 장기 실행 작업에서 중단이 요청되었는지 신호를 보내기 위해 사용할 토큰을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | 중단이 요청된 경우 true를 반환합니다. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | 중단이 요청된 경우 예외를 발생시킵니다. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

중단이 요청된 경우 true를 반환합니다.

**반환:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

중단이 요청된 경우 예외를 발생시킵니다.