---
title: SmartArtNode
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili node dari objek SmartArt
type: docs
url: /id/com.aspose.slides/smartartnode/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Mewakili node dari objek SmartArt
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Mengembalikan koleksi semua node anak dari node saat ini. |
| [getShapes()](#getShapes--) | Mengembalikan koleksi semua shape yang terkait dengan node. |
| [getTextFrame()](#getTextFrame--) | Mengembalikan teks frame dari node. |
| [isAssistant()](#isAssistant--) | Mengembalikan atau mengatur node sebagai asisten. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Mengembalikan atau mengatur node sebagai asisten. |
| [getLevel()](#getLevel--) | Mengembalikan tingkat nesting dari node. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Mengembalikan objek FillFormat yang berisi properti format isian untuk bullet node. |
| [getPosition()](#getPosition--) | Mengembalikan atau mengatur posisi berbasis nol dari node di antara node saudara. |
| [setPosition(int value)](#setPosition-int-) | Mengembalikan atau mengatur posisi berbasis nol dari node di antara node saudara. |
| [isHidden()](#isHidden--) | Mengembalikan true jika node ini adalah node tersembunyi dalam model data. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Mengembalikan atau mengatur jenis layout diagram organisasi yang terkait dengan node saat ini. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Mengembalikan atau mengatur jenis layout diagram organisasi yang terkait dengan node saat ini. |
| [remove()](#remove--) | Menghapus node saat ini. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Mengembalikan koleksi semua node anak dari node saat ini. Baca-saja [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Mengembalikan:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Mengembalikan koleksi semua shape yang terkait dengan node. Baca-saja [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Mengembalikan:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Mengembalikan teks frame dari node. Baca-saja [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Mengembalikan atau mengatur node sebagai asisten. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Mengembalikan atau mengatur node sebagai asisten. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Mengembalikan tingkat nesting dari node. Baca-saja int.

**Mengembalikan:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Mengembalikan objek FillFormat yang berisi properti format isian untuk bullet node. Catatan: dapat mengembalikan null untuk tipe tertentu dari layout SmartArt yang tidak menyediakan bullet untuk node. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Mengembalikan atau mengatur posisi berbasis nol dari node di antara node saudara. Baca/tulis int.

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Mengembalikan atau mengatur posisi berbasis nol dari node di antara node saudara. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Mengembalikan true jika node ini adalah node tersembunyi dalam model data. Baca-saja boolean.

**Mengembalikan:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Mengembalikan atau mengatur jenis layout diagram organisasi yang terkait dengan node saat ini. Baca/tulis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Mengembalikan:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Mengembalikan atau mengatur jenis layout diagram organisasi yang terkait dengan node saat ini. Baca/tulis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Menghapus node saat ini.

**Mengembalikan:**
boolean - true jika berhasil dihapus, jika tidak false