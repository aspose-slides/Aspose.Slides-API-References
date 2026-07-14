---
title: PptReadException
second_title: Aspose.Slides for Android용 Java API 참조
description: 프레젠테이션 읽기 오류가 발생했을 때 발생하는 예외를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/pptreadexception/
---
**상속:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.PptException](../../com.aspose.slides/pptexception)
```
public class PptReadException extends PptException
```

프레젠테이션 읽기 오류 발생 시 발생하는 예외를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PptReadException()](#PptReadException--) | 기본 생성자. |
| [PptReadException(String message)](#PptReadException-java.lang.String-) | 예외에 메시지를 추가할 수 있는 생성자. |
| [PptReadException(String message, Exception exception)](#PptReadException-java.lang.String-java.lang.Exception-) | 메시지와 내포된 예외를 포함하는 예외를 위한 생성자. |
### PptReadException() {#PptReadException--}
```
public PptReadException()
```

기본 생성자.

### PptReadException(String message) {#PptReadException-java.lang.String-}
```
public PptReadException(String message)
```

예외에 메시지를 추가할 수 있는 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | message |

### PptReadException(String message, Exception exception) {#PptReadException-java.lang.String-java.lang.Exception-}
```
public PptReadException(String message, Exception exception)
```

메시지와 내포된 예외를 포함하는 예외를 위한 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.Exception | 원본 예외 |