---
title: MasterTheme
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет главную тему.
type: docs
url: /ru/com.aspose.slides/mastertheme/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Представляет главную тему.
## Методы

| Метод | Описание |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Возвращает цветовую схему. |
| [getFontScheme()](#getFontScheme--) | Возвращает схему шрифтов. |
| [getFormatScheme()](#getFormatScheme--) | Возвращает схему формата фигур. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Возвращает коллекцию дополнительных цветовых схем. |
| [getName()](#getName--) | Возвращает имя темы. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает имя темы. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Возвращает цветовую схему. Только для чтения [IColorScheme](../../com.aspose.slides/icolorscheme).

**Возвращаемое значение:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Возвращает схему шрифтов. Только для чтения [IFontScheme](../../com.aspose.slides/ifontscheme).

**Возвращаемое значение:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Возвращает схему формата фигур. Только для чтения [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Возвращаемое значение:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Возвращает коллекцию дополнительных цветовых схем. Эти схемы не влияют на внешний вид презентации, их можно выбрать в качестве основной цветовой схемы для слайда. Только для чтения [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Возвращаемое значение:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```

Возвращает имя темы. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Возвращает имя темы. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long