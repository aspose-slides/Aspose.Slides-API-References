---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective format scheme properties.
type: docs
url: /ru/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства схемы формата.

--------------------

Этот интерфейс используется как часть [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getFillStyles(Integer styleColor)](#getFillStyles-java.lang.Integer-) | Возвращает коллекцию стилей заливки, определённых темой. |
| [getLineStyles(Integer styleColor)](#getLineStyles-java.lang.Integer-) | Возвращает коллекцию стилей линий, определённых темой. |
| [getEffectStyles(Integer styleColor)](#getEffectStyles-java.lang.Integer-) | Возвращает коллекцию стилей эффектов, определённых темой. |
| [getBackgroundFillStyles(Integer styleColor)](#getBackgroundFillStyles-java.lang.Integer-) | Возвращает коллекцию фоновых стилей заливки, определённых темой. |
### getFillStyles(Integer styleColor) {#getFillStyles-java.lang.Integer-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Integer styleColor)
```

Возвращает коллекцию стилей заливки, определённых темой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.lang.Integer | Цвет java.lang.Integer |

**Возвращает:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Коллекция эффективных форматов заливки [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Integer styleColor) {#getLineStyles-java.lang.Integer-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Integer styleColor)
```

Возвращает коллекцию стилей линий, определённых темой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.lang.Integer | Цвет java.lang.Integer |

**Возвращает:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - Коллекция эффективных форматов линий [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Integer styleColor) {#getEffectStyles-java.lang.Integer-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Integer styleColor)
```

Возвращает коллекцию стилей эффектов, определённых темой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.lang.Integer | Цвет java.lang.Integer |

**Возвращает:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - Коллекция эффективных форматов эффектов [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Integer styleColor) {#getBackgroundFillStyles-java.lang.Integer-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Integer styleColor)
```

Возвращает коллекцию фоновых стилей заливки, определённых темой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.lang.Integer | Цвет java.lang.Integer |

**Возвращает:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Коллекция эффективных форматов фоновой заливки [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)