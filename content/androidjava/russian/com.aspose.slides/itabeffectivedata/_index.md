---
title: ITabEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, содержащий свойства табуляции эффективного текста.
type: docs
url: /ru/com.aspose.slides/itabeffectivedata/
---
**Все реализованные интерфейсы:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Неизменяемый объект, содержащий свойства табуляции эффективного текста.

--------------------

Этот интерфейс используется как часть [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getPosition()](#getPosition--) | Возвращает позицию табуляции. |
| [getAlignment()](#getAlignment--) | Возвращает стиль выравнивания табуляции. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Возвращает позицию табуляции. Присваивание этого свойства может изменить индекс табуляции в коллекции и сделать недействительным Enumerator. Только для чтения double.

**Возвращает:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Возвращает стиль выравнивания табуляции. Только для чтения [TabAlignment](../../com.aspose.slides/tabalignment).

**Возвращает:**
int