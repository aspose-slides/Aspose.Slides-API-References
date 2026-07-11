---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /ru/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Интерфейс обратного вызова, используемый для получения результата поиска текста.
## Методы

| Метод | Описание |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Метод обратного вызова, который получает данные о найденном тексте. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Метод обратного вызова, который получает данные о найденном тексте.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe), в котором был найден текст. |
| sourceText | java.lang.String | Исходный текст, в котором был найден текст. |
| foundText | java.lang.String | Найденный текст. |
| textPosition | int | Позиция найденного текста. |