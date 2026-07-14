---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android Java API 참조
description: 소스 를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

소스 를 나타냅니다 [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getToken()](#getToken--) | 새 토큰을 이 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)에 바인딩하여 반환합니다. |
| [isInterruptionRequested()](#isInterruptionRequested--) | 중단이 요청된 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [interrupt()](#interrupt--) | 중단 요청을 초기화합니다. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

새 토큰을 이 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)에 바인딩하여 반환합니다.

**반환:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

중단이 요청된 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다.

**반환:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

중단 요청을 초기화합니다.