---
title: CellCircularReferenceException
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 수식이 직접 또는 간접적으로 자신의 셀을 참조하는 경우와 같이 하나 이상의 순환 참조가 감지될 때 발생하는 예외입니다.
type: docs
url: /ko/com.aspose.slides/cellcircularreferenceexception/
---
**상속:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

공식이 직접 또는 간접적으로 자신의 셀을 참조하는 경우와 같이 하나 이상의 순환 참조가 감지될 때 발생하는 예외입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 새 인스턴스를 초기화합니다. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | 지정된 오류 메시지와 함께 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 새 인스턴스를 초기화합니다. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | 지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조와 함께 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 새 인스턴스를 초기화합니다. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | 지정된 오류 메시지와 순환 셀 참조와 함께 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getReference()](#getReference--) | 순환 셀 참조를 가져옵니다. |

### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 새 인스턴스를 초기화합니다.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

지정된 오류 메시지를 사용하여 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 새 인스턴스를 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조와 함께 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 새 인스턴스를 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열. |
| innerException | java.lang.RuntimeException | 현재 예외의 원인인 예외. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

지정된 오류 메시지와 순환 셀 참조와 함께 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 새 인스턴스를 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열. |
| reference | java.lang.String | 순환 셀 참조. |

### getReference() {#getReference--}
```
public final String getReference()
```

순환 셀 참조를 가져옵니다.

**반환값:**
java.lang.String