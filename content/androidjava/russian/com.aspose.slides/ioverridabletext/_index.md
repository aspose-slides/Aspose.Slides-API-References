---
title: IOverridableText
second_title: Aspose.Slides для Android через справочник Java API
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
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Может содержать богато отформатированный текст. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Инициализирует TextFrameForOverriding текстом в параметре "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Может содержать богато отформатированный текст. Если это свойство не равно null, то значение этого отформатированного текста переопределяет авто-сгенерированный текст. Авто-сгенерированный текст является неявным свойством подписи данных, подписи единицы отображения оси значений, заголовка оси, заголовка диаграммы, подписи линии тренда. Авто-сгенерированный текст форматируется с помощью свойства IFormattedTextContainer.TextFormat. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Инициализирует TextFrameForOverriding текстом в параметре "text". Если TextFrameForOverriding уже инициализирован, то просто изменяет его текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для нового TextFrameForOverriding. |

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe) - Текстовый кадр [ITextFrame](../../com.aspose.slides/itextframe)