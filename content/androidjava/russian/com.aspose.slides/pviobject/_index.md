---
title: PVIObject
second_title: Aspose.Slides для Android через справочник Java API
description: Инкапсулирует базовую сервисную инфраструктуру для объектов, которые могут быть объектом наследования значений свойств.
type: docs
url: /ru/com.aspose.slides/pviobject/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)  
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Инкапсулирует базовую сервисную инфраструктуру для объектов, которые могут быть объектом наследования значений свойств.

## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Сравнивает с указанным объектом. |
| [hashCode()](#hashCode--) | Возвращает хеш-код. |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Возвращает родителя IPresentationComponent. Только для чтения [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Возвращаемое значение:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**Возвращаемое значение:**  
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Возвращает базовый слайд. Только для чтения [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращаемое значение:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Возвращает презентацию. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**  
[Presentation](../../com.aspose.slides/presentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Сравнивает с указанным объектом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения. |

**Возвращаемое значение:**  
boolean — true, если объекты равны, иначе false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Возвращает хеш-код.

**Возвращаемое значение:**  
int — Хеш-код.