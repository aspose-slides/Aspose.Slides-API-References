---
title: InterruptionTokenSource
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 소스가 되는 것을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/interruptiontokensource/
---
**상속:**
java.lang.Object
```
public class InterruptionTokenSource
```

[InterruptionToken](../../com.aspose.slides/interruptiontoken)의 소스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | 새로운 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getToken()](#getToken--) | 이 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)에 연결된 새로운 토큰을 반환합니다. |
| [isInterruptionRequested()](#isInterruptionRequested--) | 중단 요청이 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [interrupt()](#interrupt--) | 중단 요청을 초기화합니다. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```


[InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)를 새로 생성합니다.

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```


이 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)에 연결된 새로운 토큰을 반환합니다.

**반환:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


중단 요청이 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

**반환:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```


중단 요청을 초기화합니다.