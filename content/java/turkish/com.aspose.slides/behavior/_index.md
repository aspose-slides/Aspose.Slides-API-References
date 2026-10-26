---
title: Behavior
second_title: Aspose.Slides için Java API Referansı
description: Efektin temel sınıf davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/behavior/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Efektin temel sınıf davranışını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Animasyon davranışlarının birikip birikmediğini gösterir. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Animasyon davranışlarının birikip birikmediğini gösterir. |
| [getAdditive()](#getAdditive--) | Mevcut animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini gösterir. |
| [setAdditive(int value)](#setAdditive-int-) | Mevcut animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini gösterir. |
| [getProperties()](#getProperties--) | Davranışın özelliklerini temsil eder. |
| [getTiming()](#getTiming--) | Efekt davranışı için zamanlama özelliklerini temsil eder. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Efekt davranışı için zamanlama özelliklerini temsil eder. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Sadece okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Animasyon davranışlarının birikip birikmediğini gösterir. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Animasyon davranışlarının birikip birikmediğini gösterir. Okunabilir/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Mevcut animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini gösterir. Okunabilir/yazılabilir [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Döndürür:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Mevcut animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini gösterir. Okunabilir/yazılabilir [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Davranışın özelliklerini temsil eder. Sadece okunabilir [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Döndürür:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Efekt davranışı için zamanlama özelliklerini temsil eder. Okunabilir/yazılabilir [ITiming](../../com.aspose.slides/itiming).

**Döndürür:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Efekt davranışı için zamanlama özelliklerini temsil eder. Okunabilir/yazılabilir [ITiming](../../com.aspose.slides/itiming).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |