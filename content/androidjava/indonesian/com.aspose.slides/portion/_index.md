---
title: Portion
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili bagian teks di dalam sebuah paragraf teks.
type: docs
url: /id/com.aspose.slides/portion/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Mewakili bagian teks di dalam sebuah paragraf teks.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Portion()](#Portion--) | Menginisialisasi instance baru dari kelas Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Menginisialisasi instance baru dari kelas Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Menginisialisasi instance baru dari kelas Portion. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Mengembalikan objek pemformatan yang berisi properti pemformatan yang ditetapkan secara eksplisit pada bagian teks tanpa penerapan pewarisan. |
| [getText()](#getText--) | Mendapatkan atau mengatur teks biasa dari sebuah bagian. |
| [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks biasa dari sebuah bagian. |
| [getField()](#getField--) | Mengembalikan field dari bagian ini. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Mengonversi bagian ini menjadi field yang diperbarui secara otomatis. |
| [addField(String internalString)](#addField-java.lang.String-) | Mengonversi bagian ini menjadi field yang diperbarui secara otomatis. |
| [removeField()](#removeField--) | Mengonversi bagian field ini menjadi bagian sederhana. |
| [getRect()](#getRect--) | Mendapatkan koordinat rect yang membatasi bagian. |
| [getCoordinates()](#getCoordinates--) | Mendapatkan koordinat awal bagian. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari sebuah teks. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari sebuah teks. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Menginisialisasi instance baru dari kelas Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Menginisialisasi instance baru dari kelas Portion.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Menginisialisasi instance baru dari kelas Portion.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Mengembalikan objek pemformatan yang berisi properti pemformatan yang ditetapkan secara eksplisit pada bagian teks tanpa penerapan pewarisan. Hanya-baca [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Objek pemformatan berisi parameter pemformatan yang didefinisikan hanya untuk bagian saat ini, data yang diwariskan tidak diterapkan.

Untuk mendapatkan nilai efektif termasuk yang diwariskan, gunakan metode [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Mengembalikan:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Mendapatkan atau mengatur teks biasa dari sebuah bagian. Baca/tulis String.

Nilai: Teks.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Mendapatkan atau mengatur teks biasa dari sebuah bagian. Baca/tulis String.

Nilai: Teks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Mengembalikan field dari bagian ini. Hanya-baca [IField](../../com.aspose.slides/ifield).

**Mengembalikan:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Mengonversi bagian ini menjadi field yang diperbarui secara otomatis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Mengonversi bagian ini menjadi field yang diperbarui secara otomatis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| internalString | java.lang.String | Nama internal dari FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Mengonversi bagian field ini menjadi bagian sederhana.

### getRect() {#getRect--}
```
public final RectF getRect()
```

Mendapatkan koordinat rect yang membatasi bagian. Rect mencakup semua baris teks dalam bagian, termasuk yang kosong.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Mendapatkan koordinat awal bagian. Koordinat X titik mewakili awal bagian dari karakter pertama termasuk bearing sisi kiri. Koordinat Y termasuk bearing sisi atas.

**Mengembalikan:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari sebuah teks. Hanya-baca [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari sebuah teks. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject