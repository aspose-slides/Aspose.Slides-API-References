---
title: IOverridableText
second_title: Справочник API Aspose.Slides для Java
description: Представляет переопределяемый текст для диаграммы.
type: docs
url: /ru/com.aspose.slides/ioverridabletext/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Представляет переопределяемый текст для диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Может содержать форматированный текст. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Инициализировать TextFrameForOverriding текстом из параметра "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Может содержать форматированный текст. Если это свойство не равно null, то это значение форматированного текста переопределяет автоматически сгенерированный текст. Автоматически сгенерированный текст является неявным свойством подписи данных, подписи единицы измерения значениевой оси, заголовка оси, заголовка диаграммы, подписи тренд-линии. Автоматически сгенерированный текст форматируется с помощью свойства IFormattedTextContainer.TextFormat. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Инициализировать TextFrameForOverriding текстом из параметра "text". Если TextFrameForOverriding уже инициализирован, то просто изменяет его текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для нового TextFrameForOverriding. |

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe) - Текстовый кадр [ITextFrame](../../com.aspose.slides/itextframe)