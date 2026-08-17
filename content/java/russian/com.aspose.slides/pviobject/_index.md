---
title: PVIObject
second_title: Aspose.Slides для справочника API Java
description: Инкапсулирует базовую сервисную инфраструктуру для объектов, которые могут быть субъектом наследования значений свойства.
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

Инкапсулирует базовую сервисную инфраструктуру для объектов, которые могут быть субъектом наследования значений свойства.

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

Возвращает объект Parent_Immediate. Только чтение IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только чтение long.

**Возвращает:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Возвращает родительский IPresentationComponent. Только чтение [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Возвращает:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**Возвращает:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Возвращает базовый слайд. Только чтение [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращает:**
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Возвращает презентацию. Только чтение [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
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

**Возвращает:**
boolean - true, если объекты равны, иначе false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Возвращает хеш-код.

**Возвращает:**
int - Хеш-код.