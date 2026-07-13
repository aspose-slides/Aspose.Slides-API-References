---
title: TextAnimation
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili animasi teks.
type: docs
url: /id/com.aspose.slides/textanimation/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Mewakili animasi teks.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Tambahkan efek baru ke akhir urutan saat ini hingga akhir animasi teks grup. |
| [getBuildType()](#getBuildType--) | Daftar tipe build (untuk contoh. |
| [setBuildType(int value)](#setBuildType-int-) | Daftar tipe build (untuk contoh. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Efek bentuk terkait dengan grup atau tidak (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Efek bentuk terkait dengan grup atau tidak (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Tambahkan efek baru ke akhir urutan saat ini hingga akhir animasi teks grup. Hanya valid jika jumlah paragraf teks sama atau lebih besar daripada jumlah efek dalam grup ini!

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
public final int getBuildType()
```

Daftar tipe build (misalnya Paragraf 1,2,3, Semua Sekaligus) dari animasi teks. Baca/tulis [BuildType](../../com.aspose.slides/buildtype).

**Mengembalikan:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

Daftar tipe build (misalnya Paragraf 1,2,3, Semua Sekaligus) dari animasi teks. Baca/tulis [BuildType](../../com.aspose.slides/buildtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

Efek bentuk terkait dengan grup atau tidak (null). Baca/tulis [IEffect](../../com.aspose.slides/ieffect).

**Mengembalikan:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

Efek bentuk terkait dengan grup atau tidak (null). Baca/tulis [IEffect](../../com.aspose.slides/ieffect).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |