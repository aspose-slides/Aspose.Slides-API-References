---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: Stores theme-defined fonts.
type: docs
url: /id/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Menyimpan font yang ditetapkan oleh tema.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMinor()](#getMinor--) | Mengembalikan koleksi font untuk bagian "body" slide. |
| [getMajor()](#getMajor--) | Mengembalikan koleksi font untuk bagian "heading" slide. |
| [getName()](#getName--) | Mengembalikan nama skema font. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan nama skema font. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Mengembalikan koleksi font untuk bagian "body" slide. Hanya-baca [IFonts](../../com.aspose.slides/ifonts).

**Mengembalikan:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Mengembalikan koleksi font untuk bagian "heading" slide. Hanya-baca [IFonts](../../com.aspose.slides/ifonts).

**Mengembalikan:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Mengembalikan nama skema font. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Mengembalikan nama skema font. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |