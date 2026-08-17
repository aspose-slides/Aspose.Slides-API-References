---
title: IBehavior
second_title: Aspose.Slides için Java API Referansı
description: Efektin temel sınıf davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Efektin temel sınıf davranışını temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Represents whether animation behaviors are accumulated. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Represents whether animation behaviors are accumulated. |
| [getAdditive()](#getAdditive--) | Represents whether the current animation behavior is combined with other running animations. |
| [setAdditive(int value)](#setAdditive-int-) | Represents whether the current animation behavior is combined with other running animations. |
| [getProperties()](#getProperties--) | Represents properties of behavior. |
| [getTiming()](#getTiming--) | Represents timing properties for the effect behavior. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Represents timing properties for the effect behavior. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Animasyon davranışlarının birikip birikmediğini temsil eder. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Animasyon davranışlarının birikip birikmediğini temsil eder. Okunur/Yazılır [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini temsil eder. Okunur/Yazılır [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Döndürür:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirildiğini temsil eder. Okunur/Yazılır [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Davranışın özelliklerini temsil eder. Salt Okunur [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Döndürür:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Efekt davranışı için zamanlama özelliklerini temsil eder. Okunur/Yazılır [ITiming](../../com.aspose.slides/itiming).

**Döndürür:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Efekt davranışı için zamanlama özelliklerini temsil eder. Okunur/Yazılır [ITiming](../../com.aspose.slides/itiming).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |