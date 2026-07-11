---
title: ImageTransformOperationFactory
second_title: Aspose.Slides для Android через справочник Java API
description: Позволяет создавать операции преобразования изображений
type: docs
url: /ru/com.aspose.slides/imagetransformoperationfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Позволяет создавать операции преобразования изображений

--------------------

Для совместимости с COM.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Создает Alpha BiLevel effect. |
| [createAlphCeiling()](#createAlphCeiling--) | Создает Alpha Ceiling effect. |
| [createAlphaFloor()](#createAlphaFloor--) | Создает Alpha floor effect. |
| [createAlphaInverse()](#createAlphaInverse--) | Создает Alpha inverse effect. |
| [createAlphaModulate()](#createAlphaModulate--) | Создает Alpha modulate effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Создает Alpha modulate fixed effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Создает Alpha replace effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Создает BiLevel effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Создает Blur effect. |
| [createColorChange()](#createColorChange--) | Создает Color change effect. |
| [createColorReplace()](#createColorReplace--) | Создает Color replace effect. |
| [createDuotone()](#createDuotone--) | Создает Duotone effect. |
| [createFillOverlay()](#createFillOverlay--) | Создает Fill overlay effect. |
| [createGrayScale()](#createGrayScale--) | Создает Gray scale effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Создает Hue Saturation Luminance effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Создает Luminance effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Создает Tint effect. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Создает Alpha BiLevel effect.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Порог. |

**Возвращаемое значение:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Создает Alpha Ceiling effect.

**Возвращаемое значение:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Создает Alpha floor effect.

**Возвращаемое значение:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Создает Alpha inverse effect.

**Возвращаемое значение:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Создает Alpha modulate effect.

**Возвращаемое значение:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Создает Alpha modulate fixed effect.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| amount | float | Amount. |

**Возвращаемое значение:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Создает Alpha replace effect.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | float | Alpha |

**Возвращаемое значение:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


Создает BiLevel effect.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Порог. |

**Возвращаемое значение:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Создает Blur effect.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| radius | double | Радиус. |
| grow | boolean | Grow. |

**Возвращаемое значение:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Создает Color change effect.

**Возвращаемое значение:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Создает Color replace effect.

**Возвращаемое значение:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Создает Duotone effect.

**Возвращаемое значение:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Создает Fill overlay effect.

**Возвращаемое значение:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Создает Gray scale effect.

**Возвращаемое значение:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Создает Hue Saturation Luminance effect.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Возвращаемое значение:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Создает Luminance effect.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Возвращаемое значение:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Создает Tint effect.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Возвращаемое значение:**
[ITint](../../com.aspose.slides/itint) - Tint effect.