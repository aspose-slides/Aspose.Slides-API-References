---
title: PptxException
second_title: Java API 참조를 통한 Aspose.Slides for Android
description: 표준 내부 예외 유형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/pptxexception/
---
**상속:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

표준 내부 예외 유형을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PptxException()](#PptxException--) | 기본 생성자. |
| [PptxException(String message)](#PptxException-java.lang.String-) | 예외에 메시지를 추가할 수 있는 생성자. |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | 메시지와 포함된 예외를 포함하는 예외에 대한 생성자. |

### PptxException() {#PptxException--}
```
public PptxException()
```

기본 생성자.

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```

예외에 메시지를 추가할 수 있는 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | message |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```

메시지와 포함된 예외를 포함하는 예외에 대한 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |