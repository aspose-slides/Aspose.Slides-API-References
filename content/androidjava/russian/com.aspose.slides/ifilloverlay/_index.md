---
title: IFillOverlay
second_title: Aspose.Slides для Android через справку Java API
description: Представляет эффект наложения заливки.
type: docs
url: /ru/com.aspose.slides/ifilloverlay/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Представляет эффект наложения заливки. Наложение заливки может использоваться для указания дополнительной заливки объекта и смешивания двух заливок вместе.
## Методы

| Метод | Описание |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Формат заливки. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Чтение/запись [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Возвращаемое значение:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Чтение/запись [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Формат заливки. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)