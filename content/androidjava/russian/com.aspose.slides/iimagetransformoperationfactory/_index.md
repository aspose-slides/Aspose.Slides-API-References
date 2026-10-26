---
title: IImageTransformOperationFactory
second_title: Aspose.Slides для Android через Java API Reference
description: Позволяет создавать экземпляры эффектов изображений
type: docs
url: /ru/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Позволяет создавать экземпляры эффектов изображений

--------------------

Для COM-интерфейса.
## Методы

| Метод | Описание |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Создает эффект Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Создает эффект Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Создает эффект Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Создает эффект Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Создает эффект Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Создает эффект Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Создает эффект Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Создает эффект BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Создает эффект Blur. |
| [createColorChange()](#createColorChange--) | Создает эффект Color change. |
| [createColorReplace()](#createColorReplace--) | Создает эффект Color replace. |
| [createDuotone()](#createDuotone--) | Создает эффект Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Создает эффект Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Создает эффект Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Создает эффект Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Создает эффект Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Создает эффект Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Создает эффект Alpha BiLevel.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Порог. |

**Возврат:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - эффект Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Создает эффект Alpha Ceiling.

**Возврат:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - эффект Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Создает эффект Alpha floor.

**Возврат:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - эффект Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Создает эффект Alpha inverse.

**Возврат:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - эффект Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Создает эффект Alpha modulate.

**Возврат:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - эффект Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Создает эффект Alpha modulate fixed.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| amount | float | Количество. |

**Возврат:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - эффект Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Создает эффект Alpha replace.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | float | Alpha |

**Возврат:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - эффект Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Создает эффект BiLevel.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | float | Порог. |

**Возврат:**
[IBiLevel](../../com.aspose.slides/ibilevel) - эффект BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Создает эффект Blur.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| radius | double | Радиус. |
| grow | boolean | Grow. |

**Возврат:**
[IBlur](../../com.aspose.slides/iblur) - эффект Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Создает эффект Color change.

**Возврат:**
[IColorChange](../../com.aspose.slides/icolorchange) - эффект Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Создает эффект Color replace.

**Возврат:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - эффект Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Создает эффект Duotone.

**Возврат:**
[IDuotone](../../com.aspose.slides/iduotone) - эффект Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Создает эффект Fill overlay.

**Возврат:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - эффект Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Создает эффект Gray scale.

**Возврат:**
[IGrayScale](../../com.aspose.slides/igrayscale) - эффект Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Создает эффект Hue Saturation Luminance.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Возврат:**
[IHSL](../../com.aspose.slides/ihsl) - эффект HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Создает эффект Luminance.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | float | Яркость. |
| contrast | float | Контраст. |

**Возврат:**
[ILuminance](../../com.aspose.slides/iluminance) - эффект Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Создает эффект Tint.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Возврат:**
[ITint](../../com.aspose.slides/itint) - эффект Tint.