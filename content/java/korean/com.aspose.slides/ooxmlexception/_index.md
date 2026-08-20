---
title: OOXMLException
second_title: Aspose.Slides for Java API 참조
description: Office Open XML 파일 형식과 관련된 표준 내부 예외 유형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ooxmlexception/
---
**상속:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

Office Open XML 파일 형식과 관련된 표준 내부 예외 유형을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | 기본 생성자. |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | 예외에 메시지를 추가할 수 있는 생성자. |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | 메시지와 포함된 예외를 포함하는 예외용 생성자. |
### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```

기본 생성자.

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```

예외에 메시지를 추가할 수 있는 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 메시지 |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```

메시지와 포함된 예외를 포함하는 예외용 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 메시지 |
| exception | java.lang.RuntimeException | 원본 예외 |