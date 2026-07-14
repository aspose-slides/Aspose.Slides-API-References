---
title: CellInvalidReferenceException
second_title: Android용 Aspose.Slides Java API 참조
description: 잘못된 셀 참조가 발생했을 때 발생하는 예외입니다.
type: docs
url: /ko/com.aspose.slides/cellinvalidreferenceexception/
---
**상속:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

잘못된 셀 참조가 발견될 때 발생하는 예외입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | 새 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 클래스의 새 인스턴스를 초기화합니다. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | 지정된 오류 메시지를 사용하여 새 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 클래스의 인스턴스를 초기화합니다. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | 지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조를 사용하여 새 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 클래스의 인스턴스를 초기화합니다. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | 지정된 오류 메시지와 잘못된 셀 참조를 사용하여 새 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getReference()](#getReference--) | 잘못된 셀 참조를 가져옵니다. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

새 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 클래스의 인스턴스를 초기화합니다.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

지정된 오류 메시지를 사용하여 새 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 클래스의 인스턴스를 초기화합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열입니다. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조를 사용하여 새 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 클래스의 인스턴스를 초기화합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열입니다. |
| innerException | java.lang.RuntimeException | 현재 예외의 원인인 예외입니다. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

지정된 오류 메시지와 잘못된 셀 참조를 사용하여 새 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 클래스의 인스턴스를 초기화합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열입니다. |
| reference | java.lang.String | 잘못된 셀 참조입니다. |

### getReference() {#getReference--}
```
public final String getReference()
```

잘못된 셀 참조를 가져옵니다.

**반환값:**
java.lang.String