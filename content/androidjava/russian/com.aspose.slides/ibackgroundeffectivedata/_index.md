---
title: IBackgroundEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, содержащий эффективные свойства фона.
type: docs
url: /ru/com.aspose.slides/ibackgroundeffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

Неизменяемый объект, содержащий эффективные свойства фона.

--------------------

Этот интерфейс используется вместе с интерфейсом [IBackground](../../com.aspose.slides/ibackground) для возврата эффективных значений форматирования с применённым наследованием.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Возвращает эффективный формат заливки. |
| [getEffectFormat()](#getEffectFormat--) | Возвращает эффективный формат эффекта. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Возвращает эффективный формат заливки. Только для чтения [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Возврат:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Возвращает эффективный формат эффекта. Только для чтения [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Возврат:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)