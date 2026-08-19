---
title: SmartArtNode
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili node dari objek SmartArt
type: docs
url: /id/com.aspose.slides/smartartnode/
---
**Warisan:**
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
| [getTextFrame()](#getTextFrame--) | Mengembalikan bingkai teks node. |
| [isAssistant()](#isAssistant--) | Mengembalikan atau mengatur node sebagai asisten. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Mengembalikan atau mengatur node sebagai asisten. |
| [getLevel()](#getLevel--) | Mengembalikan level bersarang node. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Mengembalikan objek FillFormat yang berisi properti format isian untuk bullet node. |
| [getPosition()](#getPosition--) | Mengembalikan atau mengatur posisi berbasis nol node di antara node saudara. |
| [setPosition(int value)](#setPosition-int-) | Mengembalikan atau mengatur posisi berbasis nol node di antara node saudara. |
| [isHidden()](#isHidden--) | Mengembalikan true jika node ini adalah node tersembunyi dalam model data. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Mengembalikan atau mengatur tipe tata letak diagram organisasi yang terkait dengan node saat ini. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Mengembalikan atau mengatur tipe tata letak diagram organisasi yang terkait dengan node saat ini. |
| [remove()](#remove--) | Menghapus node saat ini. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


Mengembalikan koleksi semua node anak dari node saat ini. Hanya-baca [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Mengembalikan:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


Mengembalikan koleksi semua shape yang terkait dengan node. Hanya-baca [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Mengembalikan:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Mengembalikan bingkai teks node. Hanya-baca [ITextFrame](../../com.aspose.slides/itextframe).

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


Mengembalikan level bersarang node. Hanya-baca int.

**Mengembalikan:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


Mengembalikan objek FillFormat yang berisi properti format isian untuk bullet node. Catatan: dapat mengembalikan null untuk tipe layout SmartArt tertentu yang tidak menyediakan bullet untuk node. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Mengembalikan atau mengatur posisi berbasis nol node di antara node saudara. Baca/tulis int .

**Mengembalikan:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Mengembalikan atau mengatur posisi berbasis nol node di antara node saudara. Baca/tulis int .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


Mengembalikan true jika node ini adalah node tersembunyi dalam model data. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


Mengembalikan atau mengatur tipe tata letak diagram organisasi yang terkait dengan node saat ini. Baca/tulis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Mengembalikan:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


Mengembalikan atau mengatur tipe tata letak diagram organisasi yang terkait dengan node saat ini. Baca/tulis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

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
boolean - true if removed succesfully, otherwise false