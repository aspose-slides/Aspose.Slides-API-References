---
title: IColorReplaceEffectiveData
second_title: Справочник API Aspose.Slides для Java
description: Неизменяемый объект, представляющий эффект замены цвета.
type: docs
url: /ru/com.aspose.slides/icolorreplaceeffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorReplaceEffectiveData extends IEffectEffectiveData
```

Неизменяемый объект, представляющий эффект замены цвета. Все цвета эффекта заменяются на фиксированный цвет. Значения альфа не изменяются.
## Методы

| Метод | Описание |
| --- | --- |
| [getColor()](#getColor--) | Возвращает цветовой формат, который заменит цвет каждого пикселя. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

Возвращает цветовой формат, который заменит цвет каждого пикселя. Только для чтения java.awt.Color.

**Возвращаемое значение:**
java.awt.Color