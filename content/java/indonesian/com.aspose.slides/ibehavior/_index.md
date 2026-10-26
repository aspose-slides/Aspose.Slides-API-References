---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Mewakili perilaku kelas dasar dari efek.
type: docs
url: /id/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Mewakili perilaku kelas dasar dari efek.
## Methods

| Method | Description |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Mewakili apakah perilaku animasi dikumpulkan. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Mewakili apakah perilaku animasi dikumpulkan. |
| [getAdditive()](#getAdditive--) | Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. |
| [setAdditive(int value)](#setAdditive-int-) | Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. |
| [getProperties()](#getProperties--) | Mewakili properti perilaku. |
| [getTiming()](#getTiming--) | Mewakili properti timing untuk perilaku efek. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Mewakili properti timing untuk perilaku efek. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Mewakili apakah perilaku animasi dikumpulkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Mewakili apakah perilaku animasi dikumpulkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. Baca/tulis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returns:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. Baca/tulis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Mewakili properti perilaku. Baca-saja [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returns:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Mewakili properti timing untuk perilaku efek. Baca/tulis [ITiming](../../com.aspose.slides/itiming).

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Mewakili properti timing untuk perilaku efek. Baca/tulis [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |