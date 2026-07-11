---
title: IFontScheme
second_title: Aspose.Slides для Android через Java API Reference
description: Хранит шрифты, определённые темой.
type: docs
url: /ru/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Хранит шрифты, определённые темой.
## Методы

| Методы | Описание |
| --- | --- |
| [getMinor()](#getMinor--) | Возвращает коллекцию шрифтов для части слайда "body". |
| [getMajor()](#getMajor--) | Возвращает коллекцию шрифтов для части слайда "heading". |
| [getName()](#getName--) | Возвращает название схемы шрифтов. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает название схемы шрифтов. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

Возвращает коллекцию шрифтов для части слайда "body". Только для чтения [IFonts](../../com.aspose.slides/ifonts).

**Возвращаемое значение:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

Возвращает коллекцию шрифтов для части слайда "heading". Только для чтения [IFonts](../../com.aspose.slides/ifonts).

**Возвращаемое значение:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает название схемы шрифтов. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Возвращает название схемы шрифтов. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |