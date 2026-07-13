---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili perilaku kelas dasar efek.
type: docs
url: /id/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Mewakili perilaku kelas dasar efek.
## Metode

| Metode | Deskripsi |
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

**Mengembalikan:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Mewakili apakah perilaku animasi dikumpulkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. Baca/tulis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Mengembalikan:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. Baca/tulis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Mewakili properti perilaku. Baca-saja [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Mengembalikan:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Mewakili properti timing untuk perilaku efek. Baca/tulis [ITiming](../../com.aspose.slides/itiming).

**Mengembalikan:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Mewakili properti timing untuk perilaku efek. Baca/tulis [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |