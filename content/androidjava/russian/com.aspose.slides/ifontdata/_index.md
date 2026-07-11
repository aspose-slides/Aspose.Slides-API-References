---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет определение шрифта.
type: docs
url: /ru/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Представляет определение шрифта.
## Методы

| Метод | Описание |
| --- | --- |
| [getFontName()](#getFontName--) | Возвращает имя шрифта. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Возвращает имя шрифта, заменяя ссылку на тему фактическим используемым шрифтом. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Возвращает имя шрифта. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Возвращает имя шрифта, заменяя ссылку на тему фактическим используемым шрифтом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Тема, из которой следует взять имя шрифта. Ответственность за предоставление правильного значения лежит на вызывающем. |

**Возвращаемое значение:**
java.lang.String - Имя шрифта.