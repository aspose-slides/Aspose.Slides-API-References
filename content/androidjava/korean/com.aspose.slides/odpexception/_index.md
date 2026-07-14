---
title: OdpException
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 표준 내부 예외 유형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/odpexception/
---
**상속:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

표준 내부 예외 유형을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OdpException()](#OdpException--) | 기본 생성자 |
| [OdpException(String message)](#OdpException-java.lang.String-) | 예외에 메시지를 추가할 수 있는 생성자 |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | 메시지와 내부 예외를 포함하는 예외용 생성자 |
### OdpException() {#OdpException--}
```
public OdpException()
```

기본 생성자

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```

예외에 메시지를 추가할 수 있는 생성자.

**매개 변수:**
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| message | java.lang.String | message |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```

메시지와 내부 예외를 포함하는 예외용 생성자.

**매개 변수:**
| 매개 변수 | 유형 | 설명 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |