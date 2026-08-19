---
title: IFontScheme
second_title: Aspose.Slides for Java Referensi API
description: Menyimpan font yang didefinisikan dalam tema.
type: docs
url: /id/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Menyimpan font yang didefinisikan dalam tema.
## Metode

| Method | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Mengembalikan koleksi font untuk bagian "body" pada slide. |
| [getMajor()](#getMajor--) | Mengembalikan koleksi font untuk bagian "heading" pada slide. |
| [getName()](#getName--) | Mengembalikan nama skema font. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan nama skema font. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

Mengembalikan koleksi font untuk bagian "body" pada slide. Read-only [IFonts](../../com.aspose.slides/ifonts).

**Mengembalikan:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

Mengembalikan koleksi font untuk bagian "heading" pada slide. Read-only [IFonts](../../com.aspose.slides/ifonts).

**Mengembalikan:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

Mengembalikan nama skema font. Read/write String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Mengembalikan nama skema font. Read/write String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |