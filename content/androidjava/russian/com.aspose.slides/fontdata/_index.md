---
title: FontData
second_title: Справочник API Aspose.Slides для Android на Java
description: Представляет определение шрифта.
type: docs
url: /ru/com.aspose.slides/fontdata/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Представляет определение шрифта. Неизменяемый.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Создает новый объект FontData с указанным именем шрифта. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFontName()](#getFontName--) | Возвращает имя шрифта. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Возвращает имя шрифта, заменяя ссылку на тему фактическим используемым шрифтом. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два экземпляра FontData. |
| [hashCode()](#hashCode--) | Служит хеш-функцией для конкретного типа, подходящей для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица. |
| [toString()](#toString--) | Возвращает строковое представление. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Создает новый объект FontData с указанным именем шрифта.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Возвращает имя шрифта. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Возвращает имя шрифта, заменяя ссылку на тему фактическим используемым шрифтом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Тема, из которой следует взять имя шрифта. Ответственность за предоставление корректного значения лежит на вызывающем. Смотрите [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Возвращаемое значение:**
java.lang.String - Имя шрифта.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Определяет, равны ли два экземпляра FontData.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | FontData для сравнения с текущим FontData. |

**Возвращаемое значение:**
boolean - **true**, если указанный FontData равен текущему FontData; иначе **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Служит хеш-функцией для конкретного типа, подходящей для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.

**Возвращаемое значение:**
int - Хеш-код FontData.
### toString() {#toString--}
```
public String toString()
```

Возвращает строковое представление.

**Возвращаемое значение:**
java.lang.String - Строковое представление.