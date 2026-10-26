---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Represent text animation.
type: docs
url: /id/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Mewakili animasi teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Menambahkan efek baru ke akhir urutan saat ini hingga akhir animasi teks grup. |
| [getBuildType()](#getBuildType--) | Daftar tipe build (untuk contoh. |
| [setBuildType(int value)](#setBuildType-int-) | Daftar tipe build (untuk contoh. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Efek bentuk terhubung dengan grup atau tidak (null) Baca/tulis [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Efek bentuk terhubung dengan grup atau tidak (null) Baca/tulis [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Menambahkan efek baru ke akhir urutan saat ini hingga akhir animasi teks grup. Hanya valid jika jumlah paragraf teks sama atau lebih besar dari jumlah efek dalam grup ini!

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| effectType | int | Jenis efek animasi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipe efek animasi [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipe pemicu efek [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Mengembalikan:**
[IEffect](../../com.aspose.slides/ieffect) - Objek efek baru [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Daftar tipe build (misalnya Paragraf 1,2,3, Semua Sekaligus) dari animasi teks. Baca/tulis \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Mengembalikan:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Daftar tipe build (misalnya Paragraf 1,2,3, Semua Sekaligus) dari animasi teks. Baca/tulis \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Efek bentuk terhubung dengan grup atau tidak (null) Baca/tulis [IEffect](../../com.aspose.slides/ieffect).

**Mengembalikan:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Efek bentuk terhubung dengan grup atau tidak (null) Baca/tulis [IEffect](../../com.aspose.slides/ieffect).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |