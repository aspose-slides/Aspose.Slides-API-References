---
title: CellInvalidFormulaException
second_title: Справочник API Aspose.Slides для Android на Java
description: Исключение, которое выбрасывается, когда рассчитанная формула неверна или не была разобрана.
type: docs
url: /ru/com.aspose.slides/cellinvalidformulaexception/
---
**Наследование:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Исключение, которое выбрасывается, когда рассчитанная формула неверна или не была разобрана.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Создает новый экземпляр класса [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Создает новый экземпляр класса [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) с указанным сообщением об ошибке. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Создает новый экземпляр класса [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной этого исключения. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Создает новый экземпляр класса [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) с указанным сообщением об ошибке и ссылкой на ячейку, содержащую неверную формулу. |
## Методы

| Метод | Описание |
| --- | --- |
| [getReference()](#getReference--) | Получает ссылку на ячейку, содержащую неверную формулу. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```


Создает новый экземпляр класса [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```


Создает новый экземпляр класса [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) с указанным сообщением об ошибке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```


Создает новый экземпляр класса [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной этого исключения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |
| innerException | java.lang.RuntimeException | Исключение, которое является причиной текущего исключения. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```


Создает новый экземпляр класса [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) с указанным сообщением об ошибке и ссылкой на ячейку, содержащую неверную формулу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |
| reference | java.lang.String | Строка, описывающая ссылку на внутреннее исключение. |

### getReference() {#getReference--}
```
public final String getReference()
```


Получает ссылку на ячейку, содержащую неверную формулу.

**Возвращаемое значение:**
java.lang.String