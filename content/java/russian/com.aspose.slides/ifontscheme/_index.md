---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: Хранит шрифты, определённые темой.
type: docs
url: /ru/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Хранит шрифты, определённые темой.
## Методы

| Метод | Описание |
| --- | --- |
| [getMinor()](#getMinor--) | Возвращает коллекцию шрифтов для части слайда "body". |
| [getMajor()](#getMajor--) | Возвращает коллекцию шрифтов для части слайда "heading". |
| [getName()](#getName--) | Возвращает имя схемы шрифтов. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает имя схемы шрифтов. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

Возвращает коллекцию шрифтов для части слайда "body". Только для чтения [IFonts](../../com.aspose.slides/ifonts).

**Возвращает:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

Возвращает коллекцию шрифтов для части слайда "heading". Только для чтения [IFonts](../../com.aspose.slides/ifonts).

**Возвращает:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает имя схемы шрифтов. Чтение/запись String.

**Возвращает:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Возвращает имя схемы шрифтов. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |