---
title: FormatFactory
second_title: Aspose.Slides для Android через справочник Java API
description: Позволяет создавать форматы через COM-интерфейс.
type: docs
url: /ru/com.aspose.slides/formatfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Позволяет создавать форматы через COM-интерфейс.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getInstance()](#getInstance--) | Статический экземпляр фабрики форматов. |
| [createPortionFormat()](#createPortionFormat--) | Создаёт новый [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Создаёт новый [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Создаёт новый [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Статический экземпляр фабрики форматов. Только для чтения [FormatFactory](../../com.aspose.slides/formatfactory).

**Возвращает:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Создаёт новый [IPortionFormat](../../com.aspose.slides/iportionformat).

**Возвращает:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Новый формат части.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Создаёт новый [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Возвращает:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Новый формат абзаца.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Создаёт новый [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Возвращает:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Новый формат текстового фрейма.