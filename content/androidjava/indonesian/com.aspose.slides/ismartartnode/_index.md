---
title: ISmartArtNode
second_title: Aspose.Slides untuk Android via Java API Reference
description: Mewakili node diagram SmartArt.
type: docs
url: /id/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Mewakili node diagram SmartArt.
## Metode

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Mengembalikan koleksi semua node anak dari node saat ini. |
| [getShapes()](#getShapes--) | Mengembalikan koleksi semua shape yang terkait dengan node. |
| [getTextFrame()](#getTextFrame--) | Mengembalikan atau mengatur teks node. |
| [isAssistant()](#isAssistant--) | Mengembalikan atau mengatur node sebagai asisten. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Mengembalikan atau mengatur node sebagai asisten. |
| [getLevel()](#getLevel--) | Mengembalikan tingkat bersarang node. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Mengembalikan objek FillFormat yang berisi properti format isian untuk bullet node. |
| [getPosition()](#getPosition--) | Mengembalikan atau mengatur posisi berbasis nol node di antara node saudara. |
| [setPosition(int value)](#setPosition-int-) | Mengembalikan atau mengatur posisi berbasis nol node di antara node saudara. |
| [isHidden()](#isHidden--) | Mengembalikan true jika node ini merupakan node tersembunyi dalam model data. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Mengembalikan atau mengatur jenis tata letak bagan organisasi yang terkait dengan node saat ini. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Mengembalikan atau mengatur jenis tata letak bagan organisasi yang terkait dengan node saat ini. |
| [remove()](#remove--) | Menghapus node saat ini. |

### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Mengembalikan koleksi semua node anak dari node saat ini. Hanya-baca [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Mengembalikan:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Mengembalikan koleksi semua shape yang terkait dengan node. Hanya-baca [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Mengembalikan:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Mengembalikan atau mengatur teks node. Hanya-baca [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)

### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Mengembalikan atau mengatur node sebagai asisten. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Mengembalikan atau mengatur node sebagai asisten. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Mengembalikan tingkat bersarang node. Hanya-baca int.

**Mengembalikan:**
int

### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Mengembalikan objek FillFormat yang berisi properti format isian untuk bullet node. Catatan: dapat mengembalikan null untuk jenis tata letak SmartArt tertentu yang tidak menyediakan bullet untuk node. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Mengembalikan atau mengatur posisi berbasis nol node di antara node saudara. Baca/tulis int.

**Mengembalikan:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Mengembalikan atau mengatur posisi berbasis nol node di antara node saudara. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Mengembalikan true jika node ini merupakan node tersembunyi dalam model data. Hanya-baca boolean.

**Mengembalikan:**
boolean

### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Mengembalikan atau mengatur jenis tata letak bagan organisasi yang terkait dengan node saat ini. Baca/tulis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Mengembalikan:**
int

### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Mengembalikan atau mengatur jenis tata letak bagan organisasi yang terkait dengan node saat ini. Baca/tulis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public abstract boolean remove()
```

Menghapus node saat ini.

**Mengembalikan:**
boolean - true if removed successfully, otherwise false.