---
title: IColorChange
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет эффект смены цвета.
type: docs
url: /ru/com.aspose.slides/icolorchange/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Представляет эффект смены цвета. Экземпляры FromColor заменяются экземплярами ToColor.
## Методы

| Метод | Описание |
| --- | --- |
| [getFromColor()](#getFromColor--) | Цвет, который будет заменён. |
| [getToColor()](#getToColor--) | Цвет, который заменит. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Цвет, который будет заменён. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Цвет, который заменит. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)