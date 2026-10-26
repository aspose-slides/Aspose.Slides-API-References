---
title: Behavior
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili perilaku kelas dasar dari efek.
type: docs
url: /id/com.aspose.slides/behavior/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Mewakili perilaku kelas dasar dari efek.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Mewakili apakah perilaku animasi diakumulasi. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Mewakili apakah perilaku animasi diakumulasi. |
| [getAdditive()](#getAdditive--) | Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. |
| [setAdditive(int value)](#setAdditive-int-) | Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. |
| [getProperties()](#getProperties--) | Mewakili properti perilaku. |
| [getTiming()](#getTiming--) | Mewakili properti timing untuk perilaku efek. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Mewakili properti timing untuk perilaku efek. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Mewakili apakah perilaku animasi diakumulasi. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Mewakili apakah perilaku animasi diakumulasi. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. Baca/tulis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Mengembalikan:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Mewakili apakah perilaku animasi saat ini digabungkan dengan animasi lain yang sedang berjalan. Baca/tulis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Mewakili properti perilaku. Baca-saja [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Mengembalikan:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Mewakili properti timing untuk perilaku efek. Baca/tulis [ITiming](../../com.aspose.slides/itiming).

**Mengembalikan:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Mewakili properti timing untuk perilaku efek. Baca/tulis [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |