---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Неизменяемый объект, содержащий свойства эффективной схемы форматирования.
type: docs
url: /ru/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

Неизменяемый объект, содержащий свойства эффективной схемы форматирования.

--------------------

Этот интерфейс используется как часть [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getFillStyles(Color styleColor)](#getFillStyles-java.awt.Color-) | Возвращает коллекцию стилей заливки, определённых темой. |
| [getLineStyles(Color styleColor)](#getLineStyles-java.awt.Color-) | Возвращает коллекцию стилей линий, определённых темой. |
| [getEffectStyles(Color styleColor)](#getEffectStyles-java.awt.Color-) | Возвращает коллекцию стилей эффектов, определённых темой. |
| [getBackgroundFillStyles(Color styleColor)](#getBackgroundFillStyles-java.awt.Color-) | Возвращает коллекцию стилей фоновой заливки, определённых темой. |
### getFillStyles(Color styleColor) {#getFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Color styleColor)
```


Возвращает коллекцию стилей заливки, определённых темой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Возвращаемое значение:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Коллекция эффективных форматов заливки [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Color styleColor) {#getLineStyles-java.awt.Color-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Color styleColor)
```


Возвращает коллекцию стилей линий, определённых темой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Возвращаемое значение:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - Коллекция эффективных форматов линий [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Color styleColor) {#getEffectStyles-java.awt.Color-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Color styleColor)
```


Возвращает коллекцию стилей эффектов, определённых темой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Возвращаемое значение:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - Коллекция эффективных стилей эффектов [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Color styleColor) {#getBackgroundFillStyles-java.awt.Color-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Color styleColor)
```


Возвращает коллекцию стилей фоновой заливки, определённых темой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Возвращаемое значение:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - Коллекция эффективных форматов фоновой заливки [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)