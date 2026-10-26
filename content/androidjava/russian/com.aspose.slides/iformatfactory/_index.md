---
title: IFormatFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create formats via COM interface.
type: docs
url: /ru/com.aspose.slides/iformatfactory/
---```
public interface IFormatFactory
```

Позволяет создавать форматы через COM interface.
## Методы

| Метод | Описание |
| --- | --- |
| [createPortionFormat()](#createPortionFormat--) | Создает новый [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Создает новый [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Создает новый [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### createPortionFormat() {#createPortionFormat--}
```
public abstract IPortionFormat createPortionFormat()
```


Создает новый [IPortionFormat](../../com.aspose.slides/iportionformat).

**Возвращает:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Новый формат части.
### createParagraphFormat() {#createParagraphFormat--}
```
public abstract IParagraphFormat createParagraphFormat()
```


Создает новый [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Возвращает:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Новый формат абзаца.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public abstract ITextFrameFormat createTextFrameFormat()
```


Создает новый [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Возвращает:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Новый формат текстового фрейма.