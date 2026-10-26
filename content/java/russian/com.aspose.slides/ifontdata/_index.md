---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Представляет определение шрифта.
type: docs
url: /ru/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Представляет определение шрифта.
## Методы

| Методы | Описание |
| --- | --- |
| [getFontName()](#getFontName--) | Возвращает имя шрифта. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Возвращает имя шрифта, заменяя ссылку на тему фактическим используемым шрифтом. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Возвращает имя шрифта. Только для чтения String.

**Возвращает:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Возвращает имя шрифта, заменяя ссылку на тему фактическим используемым шрифтом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Тема, из которой следует взять имя шрифта с темой. Это ответственность вызывающего предоставить корректное значение. |

**Возвращает:**
java.lang.String - Имя шрифта.