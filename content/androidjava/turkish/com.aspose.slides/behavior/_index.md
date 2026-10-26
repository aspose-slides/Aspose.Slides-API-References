---
title: Behavior
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Efektin temel sınıf davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/behavior/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Efektin temel sınıf davranışını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Animasyon davranışlarının birikip birikmediğini temsil eder. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Animasyon davranışlarının birikip birikmediğini temsil eder. |
| [getAdditive()](#getAdditive--) | Mevcut animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini temsil eder. |
| [setAdditive(int value)](#setAdditive-int-) | Mevcut animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini temsil eder. |
| [getProperties()](#getProperties--) | Davranışın özelliklerini temsil eder. |
| [getTiming()](#getTiming--) | Efekt davranışı için zamanlama özelliklerini temsil eder. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Efekt davranışı için zamanlama özelliklerini temsil eder. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Animasyon davranışlarının birikip birikmediğini temsil eder. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Animasyon davranışlarının birikip birikmediğini temsil eder. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Mevcut animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini temsil eder. Okunur/yazılabilir [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Döndürür:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Mevcut animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini temsil eder. Okunur/yazılabilir [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Davranışın özelliklerini temsil eder. Salt-okunur [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Döndürür:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Efekt davranışı için zamanlama özelliklerini temsil eder. Okunur/yazılabilir [ITiming](../../com.aspose.slides/itiming).

**Döndürür:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Efekt davranışı için zamanlama özelliklerini temsil eder. Okunur/yazılabilir [ITiming](../../com.aspose.slides/itiming).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |