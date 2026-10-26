---
title: IPortion
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebagian teks di dalam paragraf teks.
type: docs
url: /id/com.aspose.slides/iportion/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Mewakili sebagian teks di dalam paragraf teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Mengembalikan objek pemformatan yang berisi properti pemformatan yang ditetapkan secara eksplisit pada bagian teks tanpa menerapkan pewarisan. |
| [getText()](#getText--) | Mendapatkan atau mengatur teks biasa dari sebuah bagian. |
| [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks biasa dari sebuah bagian. |
| [getField()](#getField--) | Mengembalikan bidang dari bagian ini. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Mengonversi bagian ini menjadi bidang yang diperbarui secara otomatis. |
| [addField(String internalString)](#addField-java.lang.String-) | Mengonversi bagian ini menjadi bidang yang diperbarui secara otomatis. |
| [removeField()](#removeField--) | Mengonversi bagian bidang ini menjadi bagian sederhana. |
| [getRect()](#getRect--) | Dapatkan koordinat persegi panjang yang membatasi bagian. |
| [getCoordinates()](#getCoordinates--) | Dapatkan koordinat awal bagian. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Mengembalikan objek pemformatan yang berisi properti pemformatan yang ditetapkan secara eksplisit pada bagian teks tanpa menerapkan pewarisan. Baca-saja [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Obyek pemformatan berisi parameter pemformatan yang didefinisikan hanya untuk bagian saat ini, data yang diwariskan tidak diterapkan.

Untuk mendapatkan nilai efektif termasuk yang diwariskan, gunakan metode [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Mengembalikan:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Mendapatkan atau mengatur teks biasa dari sebuah bagian. Baca/tulis String.

Nilai: Teks.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Mendapatkan atau mengatur teks biasa dari sebuah bagian. Baca/tulis String.

Nilai: Teks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

Mengembalikan bidang dari bagian ini. Baca-saja [IField](../../com.aspose.slides/ifield).

**Mengembalikan:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Mengonversi bagian ini menjadi bidang yang diperbarui secara otomatis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Tipe bidang [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Mengonversi bagian ini menjadi bidang yang diperbarui secara otomatis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| internalString | java.lang.String | Nama internal dari FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```

Mengonversi bagian bidang ini menjadi bagian sederhana.
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Dapatkan koordinat persegi panjang yang membatasi bagian. Persegi panjang mencakup semua baris teks dalam bagian, termasuk yang kosong.

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
android.graphics.RectF - Persegi panjang yang membatasi bagian android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

Dapatkan koordinat awal bagian. Koordinat X titik mewakili awal bagian dari karakter pertama termasuk bearing sisi kiri. Koordinat Y termasuk bearing sisi atas.

**Mengembalikan:**
android.graphics.PointF - Koordinat awal bagian android.graphics.PointF