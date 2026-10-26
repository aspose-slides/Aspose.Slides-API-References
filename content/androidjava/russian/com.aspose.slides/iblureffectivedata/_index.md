---
title: IBlurEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
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
| [getGrow()](#getGrow--) | Определяет, следует ли расширять границы объекта в результате размытия. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Возвращает или задает радиус размытия. Только для чтения double.

**Возвращает:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Определяет, следует ли расширять границы объекта в результате размытия. True указывает, что границы расширяются, а false — что нет. Только для чтения boolean.

**Возвращает:**
boolean