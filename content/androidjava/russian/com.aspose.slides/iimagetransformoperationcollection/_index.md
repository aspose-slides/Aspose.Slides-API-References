---
title: IImageTransformOperationCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию эффектов, применяемых к изображению.
type: docs
url: /ru/com.aspose.slides/iimagetransformoperationcollection/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Представляет коллекцию эффектов, применяемых к изображению.
## Методы

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) из коллекции по его индексу. |
| [removeAt(int index)](#removeAt-int-) | Удаляет эффект изображения из коллекции по указанному индексу. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Добавляет новый эффект Alpha Bi-Level в конец коллекции. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Добавляет новый эффект Alpha Ceiling в конец коллекции. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Добавляет новый эффект Alpha Floor в конец коллекции. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Добавляет новый эффект Alpha Inverse в конец коллекции. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Добавляет новый эффект Alpha Modulate в конец коллекции. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Добавляет новый эффект Alpha Modulate Fixed в конец коллекции. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Добавляет новый эффект Alpha Replace в конец коллекции. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Добавляет новый эффект Bi-Level (чёрно-белый) в конец коллекции. |
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
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```


Возвращает [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) из коллекции по его индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс элемента. |

**Возвращаемое значение:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Объект [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Удаляет эффект изображения из коллекции по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс эффекта изображения, который следует удалить. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```


Добавляет новый эффект Alpha Bi-Level в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Значение порога для эффекта Alpha Bi-Level. |

**Возвращаемое значение:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Индекс нового эффекта изображения в коллекции.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```


Добавляет новый эффект Alpha Ceiling в конец коллекции.

**Возвращаемое значение:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Индекс нового эффекта изображения в коллекции.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```


Добавляет новый эффект Alpha Floor в конец коллекции.

**Возвращаемое значение:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Индекс нового эффекта изображения в коллекции.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```


Добавляет новый эффект Alpha Inverse в конец коллекции.

**Возвращаемое значение:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Индекс нового эффекта изображения в коллекции.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```


Добавляет новый эффект Alpha Modulate в конец коллекции.

**Возвращаемое значение:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Индекс нового эффекта изображения в коллекции.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```


Добавляет новый эффект Alpha Modulate Fixed в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| amount | float | Процентное значение, на которое нужно масштабировать альфу. |

**Возвращаемое значение:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Индекс нового эффекта изображения в коллекции.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```


Добавляет новый эффект Alpha Replace в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | float | Новое значение непрозрачности. |

**Возвращаемое значение:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Индекс нового эффекта изображения в коллекции.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```


Добавляет новый эффект Bi-Level (чёрно-белый) в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Пороговое значение яркости для эффекта Bi-Level. Значения, большие или равные порогу, становятся белыми. Значения, меньшие порога, становятся чёрными. |

**Возвращаемое значение:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Индекс нового эффекта изображения в коллекции.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```


Добавляет новый эффект Blur в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| radius | double | Радиус размытия. |
| grow | boolean | Определяет, следует ли увеличивать границы объекта в результате размытия. true — границы увеличиваются, false — не увеличиваются. |

**Возвращаемое значение:**
[IBlur](../../com.aspose.slides/iblur) - Индекс нового эффекта изображения в коллекции.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```


Добавляет новый эффект Color Change в конец коллекции.

**Возвращаемое значение:**
[IColorChange](../../com.aspose.slides/icolorchange) - Индекс нового эффекта изображения в коллекции.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```


Добавляет новый эффект Color Replacement в конец коллекции.

**Возвращаемое значение:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Индекс нового эффекта изображения в коллекции.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```


Добавляет новый эффект Duotone в конец коллекции.

**Возвращаемое значение:**
[IDuotone](../../com.aspose.slides/iduotone) - Индекс нового эффекта изображения в коллекции.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```


Добавляет новый эффект Fill Overlay в конец коллекции.

**Возвращаемое значение:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Индекс нового эффекта изображения в коллекции.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```


Добавляет новый эффект Gray Scale в конец коллекции.

**Возвращаемое значение:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Индекс нового эффекта изображения в коллекции.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```


Добавляет новый эффект Hue/Saturation/Luminance в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | float | Количество градусов, на которое изменяется оттенок. |
| saturation | float | Процент, на который изменяется насыщенность. |
| luminance | float | Процент, на который изменяется яркость. |

**Возвращаемое значение:**
[IHSL](../../com.aspose.slides/ihsl) - Индекс нового эффекта изображения в коллекции.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```


Добавляет новый эффект Luminance в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | float | Процент изменения яркости. |
| contrast | float | Процент изменения контраста. |

**Возвращаемое значение:**
[ILuminance](../../com.aspose.slides/iluminance) - Индекс нового эффекта изображения в коллекции.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```


Добавляет новый эффект Tint в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | float | Оттенок, к которому применяется тонирование. |
| amount | float | Указывает, насколько изменяется значение цвета. |

**Возвращаемое значение:**
[ITint](../../com.aspose.slides/itint) - Индекс нового эффекта изображения в коллекции.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```


Добавляет новый эффект BrightnessContrast в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | float | Процент изменения яркости. |
| contrast | float | Процент изменения контраста. |

**Возвращаемое значение:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Индекс нового эффекта изображения в коллекции.