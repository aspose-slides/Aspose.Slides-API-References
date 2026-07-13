---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Merepresentasikan referensi gaya shape.
type: docs
url: /id/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Merepresentasikan referensi gaya shape.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLineColor()](#getLineColor--) | Mengembalikan warna outline shape. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Mengembalikan atau mengatur indeks kolom garis dalam matriks gaya. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Mengembalikan atau mengatur indeks kolom garis dalam matriks gaya. |
| [getFillColor()](#getFillColor--) | Mengembalikan warna isi shape. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Mengembalikan atau mengatur indeks kolom isi shape dalam matriks gaya. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Mengembalikan atau mengatur indeks kolom isi shape dalam matriks gaya. |
| [getEffectColor()](#getEffectColor--) | Mengembalikan warna efek shape. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Mengembalikan atau mengatur indeks kolom efek shape dalam matriks gaya. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Mengembalikan atau mengatur indeks kolom efek shape dalam matriks gaya. |
| [getFontColor()](#getFontColor--) | Mengembalikan warna font shape. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Mengembalikan atau mengatur indeks font shape dalam koleksi font. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Mengembalikan atau mengatur indeks font shape dalam koleksi font. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Mengembalikan warna outline shape. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Mengembalikan atau mengatur indeks kolom garis dalam matriks gaya. Baca/tulis int.

**Mengembalikan:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Mengembalikan atau mengatur indeks kolom garis dalam matriks gaya. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Mengembalikan warna isi shape. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Mengembalikan atau mengatur indeks kolom isi shape dalam matriks gaya. 0 berarti tidak ada isi, nilai positif - indeks dalam gaya isi tema, nilai negatif - indeks dalam gaya latar belakang tema. Baca/tulis short.

**Mengembalikan:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Mengembalikan atau mengatur indeks kolom isi shape dalam matriks gaya. 0 berarti tidak ada isi, nilai positif - indeks dalam gaya isi tema, nilai negatif - indeks dalam gaya latar belakang tema. Baca/tulis short.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Mengembalikan warna efek shape. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Mengembalikan atau mengatur indeks kolom efek shape dalam matriks gaya. Baca/tulis long.

**Mengembalikan:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Mengembalikan atau mengatur indeks kolom efek shape dalam matriks gaya. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Mengembalikan warna font shape. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Mengembalikan atau mengatur indeks font shape dalam koleksi font. Baca/tulis [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Mengembalikan:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Mengembalikan atau mengatur indeks font shape dalam koleksi font. Baca/tulis [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |