---
title: CellInvalidReferenceException
second_title: Справочник API Aspose.Slides для Java
description: Исключение, которое выбрасывается при обнаружении неверной ссылки на ячейку.
type: docs
url: /ru/com.aspose.slides/cellinvalidreferenceexception/
---
**Наследование:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Исключение, которое выбрасывается при обнаружении неверной ссылки на ячейку.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Инициализирует новый экземпляр класса [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Инициализирует новый экземпляр класса [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) с указанным сообщением об ошибке. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Инициализирует новый экземпляр класса [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, которое является причиной этого исключения. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) с указанным сообщением об ошибке и неверной ссылкой на ячейку. |
## Методы

| Метод | Описание |
| --- | --- |
| [getReference()](#getReference--) | Получает неверную ссылку на ячейку. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```


Инициализирует новый экземпляр класса [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```


Инициализирует новый экземпляр класса [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) с указанным сообщением об ошибке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```


Инициализирует новый экземпляр класса [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, которое является причиной этого исключения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |
| innerException | java.lang.RuntimeException | Исключение, являющееся причиной текущего исключения. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```


Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) с указанным сообщением об ошибке и неверной ссылкой на ячейку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |
| reference | java.lang.String | Неверная ссылка на ячейку. |

### getReference() {#getReference--}
```
public final String getReference()
```


Получает неверную ссылку на ячейку.

**Возвращаемое значение:**
java.lang.String