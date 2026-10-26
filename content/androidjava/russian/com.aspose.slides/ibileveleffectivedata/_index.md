---
title: IBiLevelEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, представляющий эффект Bi-Level (чёрно-белый).
type: docs
url: /ru/com.aspose.slides/ibileveleffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Неизменяемый объект, представляющий эффект Bi-Level (black/white). Входные цвета, у которых яркость меньше указанного значения порога, изменяются на черный. Входные цвета, у которых яркость больше или равна указанному значению, устанавливаются в белый. Значения альфа-эффекта не изменяются этим эффектом.
## Методы

| Метод | Описание |
| --- | --- |
| [getThreshold()](#getThreshold--) | Возвращает значение порога. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Возвращает значение порога. Только для чтения float.

**Возвращает:**
float