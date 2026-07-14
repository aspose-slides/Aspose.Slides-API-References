---
title: CellInvalidFormulaException
second_title: Android용 Aspose.Slides Java API 참조
description: 계산된 수식이 올바르지 않거나 구문 분석되지 않았을 때 발생하는 예외입니다.
type: docs
url: /ko/com.aspose.slides/cellinvalidformulaexception/
---
**상속:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

계산된 수식이 올바르지 않거나 구문 분석되지 않았을 때 발생하는 예외입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 클래스를 새 인스턴스로 초기화합니다. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 클래스를 지정된 오류 메시지와 함께 새 인스턴스로 초기화합니다. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 클래스를 지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조와 함께 새 인스턴스로 초기화합니다. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 클래스를 지정된 오류 메시지와 잘못된 수식을 포함하는 셀 참조와 함께 새 인스턴스로 초기화합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getReference()](#getReference--) | 잘못된 수식을 포함하는 셀 참조를 가져옵니다. |

### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 클래스를 새 인스턴스로 초기화합니다.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 클래스를 지정된 오류 메시지와 함께 새 인스턴스로 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열입니다. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 클래스를 지정된 오류 메시지와 이 예외의 원인인 내부 예외에 대한 참조와 함께 새 인스턴스로 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열입니다. |
| innerException | java.lang.RuntimeException | 현재 예외의 원인인 예외입니다. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 클래스를 지정된 오류 메시지와 잘못된 수식을 포함하는 셀 참조와 함께 새 인스턴스로 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 오류를 설명하는 문자열입니다. |
| reference | java.lang.String | 내부 예외에 대한 참조를 설명하는 문자열입니다. |

### getReference() {#getReference--}
```
public final String getReference()
```

잘못된 수식을 포함하는 셀 참조를 가져옵니다.

**반환값:**
java.lang.String