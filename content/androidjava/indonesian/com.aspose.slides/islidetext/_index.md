---
title: ISlideText
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili teks yang diekstraksi dari slide
type: docs
url: /id/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Mewakili teks yang diekstraksi dari slide
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getText()](#getText--) | Teks pada bentuk slide |
| [getMasterText()](#getMasterText--) | Teks pada bentuk halaman master untuk slide ini |
| [getLayoutText()](#getLayoutText--) | Teks pada bentuk halaman tata letak untuk slide ini |
| [getNotesText()](#getNotesText--) | Teks pada bentuk halaman catatan untuk slide ini |
| [getCommentsText()](#getCommentsText--) | Teks dari komentar slide |
### getText() {#getText--}
```
public abstract String getText()
```

Teks pada bentuk slide

**Mengembalikan:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

Teks pada bentuk halaman master untuk slide ini

**Mengembalikan:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

Teks pada bentuk halaman tata letak untuk slide ini

**Mengembalikan:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

Teks pada bentuk halaman catatan untuk slide ini

**Mengembalikan:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

Teks dari komentar slide

--------------------

Bidang ini kosong ketika teks diekstraksi menggunakan Arranged mode.

**Mengembalikan:**
java.lang.String