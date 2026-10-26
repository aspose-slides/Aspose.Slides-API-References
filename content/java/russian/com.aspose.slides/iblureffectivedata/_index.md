---
title: IBlurEffectiveData
second_title: Справочник API Aspose.Slides для Java
description: Неизменяемый объект, представляющий эффект размытия, применяемый ко всей фигуре, включая её заливку.
type: docs
url: /ru/com.aspose.slides/iblureffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Неизменяемый объект, представляющий эффект размытия, применяемый ко всей фигуре, включая её заливку. Все цветовые каналы, включая альфа-канал, затрагиваются.

## Методы

| Метод | Описание |
| --- | --- |
| [getRadius()](#getRadius--) | Возвращает или задает радиус размытия. |
| [getGrow()](#getGrow--) | Определяет, следует ли увеличивать границы объекта в результате размытия. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Возвращает или задает радиус размытия. Только для чтения double.

**Возвращаемое значение:**  
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Определяет, следует ли увеличивать границы объекта в результате размытия. Значение **true** указывает, что границы увеличиваются, а **false** — что нет. Только для чтения boolean.

**Возвращаемое значение:**  
boolean