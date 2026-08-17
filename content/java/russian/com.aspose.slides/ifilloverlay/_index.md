---
title: IFillOverlay
second_title: Aspose.Slides для Java: справка API
description: Представляет эффект Fill Overlay.
type: docs
url: /ru/com.aspose.slides/ifilloverlay/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Представляет эффект Fill Overlay. Fill overlay может использоваться для указания дополнительного заполнения объекта и смешивания двух заполнений вместе.
## Методы

| Метод | Описание |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
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


Fill format. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)