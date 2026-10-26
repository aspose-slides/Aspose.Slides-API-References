---
title: PptException
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 표준 내부 예외 유형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/pptexception/
---
**상속:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class PptException extends System.Exception
```

표준 내부 예외 유형을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PptException()](#PptException--) | 기본 생성자. |
| [PptException(String message)](#PptException-java.lang.String-) | 예외에 메시지를 추가할 수 있는 생성자. |
| [PptException(String message, Exception exception)](#PptException-java.lang.String-java.lang.Exception-) | 메시지와 포함된 예외를 포함하는 예외에 대한 생성자. |
### PptException() {#PptException--}
```
public PptException()
```

기본 생성자.

### PptException(String message) {#PptException-java.lang.String-}
```
public PptException(String message)
```

예외에 메시지를 추가할 수 있는 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 메시지 |

### PptException(String message, Exception exception) {#PptException-java.lang.String-java.lang.Exception-}
```
public PptException(String message, Exception exception)
```

메시지와 포함된 예외를 포함하는 예외에 대한 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 메시지 |
| exception | java.lang.Exception | 원본 예외 |