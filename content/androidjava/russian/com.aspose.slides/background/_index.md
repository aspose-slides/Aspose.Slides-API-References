---
title: Background
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет фон слайда.
type: docs
url: /ru/com.aspose.slides/background/
---
**Наследование:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**  
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject  
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Представляет фон слайда.

## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает тип заливки фона. |
| [setType(byte value)](#setType-byte-) | Возвращает тип заливки фона. |
| [getFillFormat()](#getFillFormat--) | Возвращает объект FillFormat для заливки BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает объект EffectFormat для заливки BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Возвращает объект ColorFormat для заливки BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Возвращает индекс заливки BackgroundType.Themed в коллекции тем фона. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Возвращает индекс заливки BackgroundType.Themed в коллекции тем фона. |
| [getEffective()](#getEffective--) | Получает эффективные данные фона с учётом наследования. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Возвращает родительский слайд фигуры. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию слайда. |

### getType() {#getType--}
```
public final byte getType()
```

Возвращает тип заливки фона. Чтение/запись [BackgroundType](../../com.aspose.slides/backgroundtype).

**Возвращаемое значение:**  
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Возвращает тип заливки фона. Чтение/запись [BackgroundType](../../com.aspose.slides/backgroundtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Возвращает объект FillFormat для заливки BackgroundType.OwnBackground. Только чтение [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Возвращает объект EffectFormat для заливки BackgroundType.OwnBackground. Только чтение [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Возвращаемое значение:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Возвращает объект ColorFormat для заливки BackgroundType.Themed. Только чтение [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Возвращает индекс заливки BackgroundType.Themed в коллекции тем фона. 0 означает отсутствие заливки. 1..999 — индекс. Чтение/запись int.

**Возвращаемое значение:**  
int

### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Возвращает индекс заливки BackgroundType.Themed в коллекции тем фона. 0 означает отсутствие заливки. 1..999 — индекс. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Получает эффективные данные фона с учётом наследования.

--------------------

> ```
> Этот пример демонстрирует получение эффективных свойств фона.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**  
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только чтение long.

**Возвращаемое значение:**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только чтение IDOMObject.

**Возвращаемое значение:**  
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Возвращает родительский слайд фигуры. Только чтение [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращаемое значение:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Возвращает родительскую презентацию слайда. Только чтение [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**  
[Presentation](../../com.aspose.slides/presentation)