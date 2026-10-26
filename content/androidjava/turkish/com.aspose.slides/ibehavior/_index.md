---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Efektin temel sınıf davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Efektin temel sınıf davranışını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Animasyon davranışlarının birikip birikmediğini temsil eder. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Animasyon davranışlarının birikip birikmediğini temsil eder. |
| [getAdditive()](#getAdditive--) | Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilemediğini temsil eder. |
| [setAdditive(int value)](#setAdditive-int-) | Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilemediğini temsil eder. |
| [getProperties()](#getProperties--) | Davranışın özelliklerini temsil eder. |
| [getTiming()](#getTiming--) | Efekt davranışı için zamanlama özelliklerini temsil eder. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Efekt davranışı için zamanlama özelliklerini temsil eder. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Animasyon davranışlarının birikip birikmediğini temsil eder. Okuma/Yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Animasyon davranışlarının birikip birikmediğini temsil eder. Okuma/Yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilemediğini temsil eder. Okuma/Yazma [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Döndürür:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilemediğini temsil eder. Okuma/Yazma [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Davranışın özelliklerini temsil eder. Yalnızca okuma [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Döndürür:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Efekt davranışı için zamanlama özelliklerini temsil eder. Okuma/Yazma [ITiming](../../com.aspose.slides/itiming).

**Döndürür:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Efekt davranışı için zamanlama özelliklerini temsil eder. Okuma/Yazma [ITiming](../../com.aspose.slides/itiming).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |