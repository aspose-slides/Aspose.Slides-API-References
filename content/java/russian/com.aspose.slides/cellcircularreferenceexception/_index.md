---
title: CellCircularReferenceException
second_title: Справочник API Aspose.Slides для Java
description: Исключение, которое выбрасывается, когда обнаружены одна или несколько кольцевых ссылок, при которых формула ссылается на свою собственную ячейку напрямую или косвенно.
type: docs
url: /ru/com.aspose.slides/cellcircularreferenceexception/
---
**Наследование:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Исключение, которое выбрасывается, когда обнаружены одна или несколько кольцевых ссылок, при которых формула ссылается на свою собственную ячейку напрямую или косвенно.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) с указанным сообщением об ошибке. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной этого исключения. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) с указанным сообщением об ошибке и кольцевой ссылкой на ячейку. |
## Методы

| Метод | Описание |
| --- | --- |
| [getReference()](#getReference--) | Получает кольцевую ссылку на ячейку. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) с указанным сообщением об ошибке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) с указанным сообщением об ошибке и ссылкой на внутреннее исключение, являющееся причиной этого исключения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |
| innerException | java.lang.RuntimeException | Исключение, являющееся причиной текущего исключения. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Инициализирует новый экземпляр класса [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) с указанным сообщением об ошибке и кольцевой ссылкой на ячейку.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| message | java.lang.String | Строка, описывающая ошибку. |
| reference | java.lang.String | Кольцевая ссылка на ячейку. |

### getReference() {#getReference--}
```
public final String getReference()
```

Получает кольцевую ссылку на ячейку.

**Возвращаемое значение:**
java.lang.String