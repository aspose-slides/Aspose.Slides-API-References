---
title: MasterTheme
second_title: Справочник API Aspose.Slides для Java
description: Представляет основной шаблон темы.
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

Представляет основной шаблон темы.
## Методы

| Метод | Описание |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Возвращает схему цветов. |
| [getFontScheme()](#getFontScheme--) | Возвращает схему шрифтов. |
| [getFormatScheme()](#getFormatScheme--) | Возвращает схему форматов фигур. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Возвращает коллекцию дополнительных схем цветов. |
| [getName()](#getName--) | Возвращает имя темы. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает имя темы. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


Возвращает схему цветов. Только для чтения [IColorScheme](../../com.aspose.slides/icolorscheme).

**Возвращает:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


Возвращает схему шрифтов. Только для чтения [IFontScheme](../../com.aspose.slides/ifontscheme).

**Возвращает:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


Возвращает схему форматов фигур. Только для чтения [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Возвращает:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


Возвращает коллекцию дополнительных схем цветов. Эти схемы не влияют на внешний вид презентации, их можно выбрать в качестве основной схемы цветов для слайда. Только для чтения [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Возвращает:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


Возвращает имя темы. Чтение/запись String.

**Возвращает:**
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

**Возвращает:**
long