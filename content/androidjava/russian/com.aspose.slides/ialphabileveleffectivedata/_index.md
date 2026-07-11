---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, представляющий эффект Alpha Bi-Level.
type: docs
url: /ru/com.aspose.slides/ialphabileveleffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Неизменяемый объект, представляющий эффект Alpha Bi-Level. Значения Alpha (непрозрачность), меньшие порога, изменяются на 0 (полностью прозрачные), а значения alpha, большие или равные порогу, изменяются на 100 % (полностью непрозрачные).
## Методы

| Метод | Описание |
| --- | --- |
| [getThreshold()](#getThreshold--) | Возвращает порог эффекта. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Возвращает порог эффекта. Только для чтения float.

**Возвращает:**
float