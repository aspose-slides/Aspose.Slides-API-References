---
title: IBiLevelEffectiveData
second_title: Справочник API Aspose.Slides для Java
description: Неизменяемый объект, представляющий эффект Bi-Level (черный/белый).
type: docs
url: /ru/com.aspose.slides/ibileveleffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Неизменяемый объект, представляющий эффект Bi-Level (черный/белый). Входные цвета, чья яркость меньше указанного порогового значения, преобразуются в черный. Входные цвета, чья яркость больше или равна указанному значению, устанавливаются в белый. Значения альфа-эффекта не изменяются этим эффектом.

## Методы

| Method | Описание |
| --- | --- |
| [getThreshold()](#getThreshold--) | Возвращает пороговое значение. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Возвращает пороговое значение. Только для чтения float.

**Возвращаемое значение:**
float