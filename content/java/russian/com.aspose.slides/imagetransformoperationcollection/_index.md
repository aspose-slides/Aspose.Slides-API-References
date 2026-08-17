---
title: ImageTransformOperationCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию эффектов, применяемых к изображению.
type: docs
url: /ru/com.aspose.slides/imagetransformoperationcollection/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Представляет коллекцию эффектов, применяемых к изображению.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Возвращает [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) из коллекции по его индексу. |
| [removeAt(int index)](#removeAt-int-) | Удаляет эффект изображения из коллекции по указанному индексу. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Добавляет новый эффект Alpha Bi-Level в конец коллекции. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Добавляет новый эффект Alpha Ceiling в конец коллекции. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Добавляет новый эффект Alpha Floor в конец коллекции. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Добавляет новый эффект Alpha Inverse в конец коллекции. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Добавляет новый эффект Alpha Modulate в конец коллекции. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Добавляет новый эффект Alpha Modulate Fixed в конец коллекции. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Добавляет новый эффект Alpha Replace в конец коллекции. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Добавляет новый эффект Bi-Level (чёрный/белый) в конец коллекции. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Добавляет новый эффект Blur в конец коллекции. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Добавляет новый эффект Color Change в конец коллекции. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Добавляет новый эффект Color Replacement в конец коллекции. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Добавляет новый эффект Duotone в конец коллекции. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Добавляет новый эффект Fill Overlay в конец коллекции. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Добавляет новый эффект Gray Scale в конец коллекции. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Добавляет новый эффект Hue/Saturation/Luminance в конец коллекции. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Добавляет новый эффект Luminance в конец коллекции. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Добавляет новый эффект Tint в конец коллекции. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Добавляет новый эффект BrightnessContrast в конец коллекции. |
| [size()](#size--) | Возвращает количество эффектов изображения в коллекции. |
| [isReadOnly()](#isReadOnly--) | Возвращает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Добавляет новый эффект изображения в конец коллекции. |
| [clear()](#clear--) | Удаляет все эффекты изображения из коллекции. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с указанного индекса массива. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Возвращает [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) из коллекции по его индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращает:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Объект [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет эффект изображения из коллекции по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс эффекта изображения, который следует удалить. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Добавляет новый эффект Alpha Bi-Level в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Пороговое значение для эффекта alpha bi-level. |

**Возвращает:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Индекс нового эффекта изображения в коллекции.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Добавляет новый эффект Alpha Ceiling в конец коллекции.

**Возвращает:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Индекс нового эффекта изображения в коллекции.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Добавляет новый эффект Alpha Floor в конец коллекции.

**Возвращает:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Индекс нового эффекта изображения в коллекции.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Добавляет новый эффект Alpha Inverse в конец коллекции.

**Возвращает:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Индекс нового эффекта изображения в коллекции.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Добавляет новый эффект Alpha Modulate в конец коллекции.

**Возвращает:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Индекс нового эффекта изображения в коллекции.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Добавляет новый эффект Alpha Modulate Fixed в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| amount | float | Процентное значение для масштабирования альфа. |

**Возвращает:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Индекс нового эффекта изображения в коллекции.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Добавляет новый эффект Alpha Replace в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | float | Новое значение непрозрачности. |

**Возвращает:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Индекс нового эффекта изображения в коллекции.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Добавляет новый эффект Bi-Level (чёрный/белый) в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Порог яркости для эффекта Bi-Level. Значения, большие или равные порогу, устанавливаются в белый. Значения, меньшие порога, устанавливаются в чёрный. |

**Возвращает:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Индекс нового эффекта изображения в коллекции.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Добавляет новый эффект Blur в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| radius | double | Радиус размытия. |
| grow | boolean | Указывает, следует ли расширять границы объекта в результате размытия. true означает, что границы расширяются, false — что не расширяются. |

**Возвращает:**
[IBlur](../../com.aspose.slides/iblur) - Индекс нового эффекта изображения в коллекции.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Добавляет новый эффект Color Change в конец коллекции.

**Возвращает:**
[IColorChange](../../com.aspose.slides/icolorchange) - Индекс нового эффекта изображения в коллекции.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Добавляет новый эффект Color Replacement в конец коллекции.

**Возвращает:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Индекс нового эффекта изображения в коллекции.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Добавляет новый эффект Duotone в конец коллекции.

**Возвращает:**
[IDuotone](../../com.aspose.slides/iduotone) - Индекс нового эффекта изображения в коллекции.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Добавляет новый эффект Fill Overlay в конец коллекции.

**Возвращает:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Индекс нового эффекта изображения в коллекции.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Добавляет новый эффект Gray Scale в конец коллекции.

**Возвращает:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Индекс нового эффекта изображения в коллекции.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Добавляет новый эффект Hue/Saturation/Luminance в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | float | Количество градусов, на которое изменяется оттенок. |
| saturation | float | Процент, на который изменяется насыщенность. |
| luminance | float | Процент, на который изменяется яркость. |

**Возвращает:**
[IHSL](../../com.aspose.slides/ihsl) - Индекс нового эффекта изображения в коллекции.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Добавляет новый эффект Luminance в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | float | Процент изменения яркости. |
| contrast | float | Процент изменения контрастности. |

**Возвращает:**
[ILuminance](../../com.aspose.slides/iluminance) - Индекс нового эффекта изображения в коллекции.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Добавляет новый эффект Tint в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | float | Оттенок, к которому применяется тонирование. |
| amount | float | Указывает, насколько смещается значение цвета. |

**Возвращает:**
[ITint](../../com.aspose.slides/itint) - Индекс нового эффекта изображения в коллекции.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Добавляет новый эффект BrightnessContrast в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | float | Процент изменения яркости. |
| contrast | float | Процент изменения контрастности. |

**Возвращает:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Индекс нового эффекта изображения в коллекции.
### size() {#size--}
```
public final int size()
```

Возвращает количество эффектов изображения в коллекции. Только для чтения int .

**Возвращает:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Возвращает значение, указывающее, является ли [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения. Только для чтения boolean.

**Возвращает:**
boolean - true, если [IGenericCollection](../../com.aspose.slides/igenericcollection) только для чтения; иначе false.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Добавляет новый эффект изображения в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Эффект изображения, который будет добавлен в конец коллекции. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет все эффекты изображения из коллекции.
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Определяет, содержит ли [IGenericCollection](../../com.aspose.slides/igenericcollection) конкретное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Объект, который следует найти в [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращает:**
boolean - true, если элемент найден в [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false.
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Копирует элементы [IGenericCollection](../../com.aspose.slides/igenericcollection) в массив, начиная с указанного индекса массива.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Одномерный массив, в который копируются элементы из [IGenericCollection](../../com.aspose.slides/igenericcollection). Массив должен использовать нулевую индексацию. |
| arrayIndex | int | Нулевой индекс в массиве, с которого начинается копирование. |
### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Удаляет первое вхождение конкретного объекта из [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Объект, который следует удалить из [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Возвращает:**
boolean - true, если объект был успешно удалён из [IGenericCollection](../../com.aspose.slides/igenericcollection); иначе false. Этот метод также возвращает false, если объект не найден в оригинальном [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - An java.util.Iterator for the entire collection.