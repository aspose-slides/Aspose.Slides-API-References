---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili sebuah hyperlink.
type: docs
url: /id/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Mewakili sebuah hyperlink.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getActionType()](#getActionType--) | Mengembalikan tipe aksi HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Menentukan URL eksternal. Jika properti ini menjadi tidak null maka properti TargetSlide menjadi null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Mewakili sebuah hyperlink yang ditetapkan untuk bagian ini tanpa memperhatikan konten sebenarnya dari bagian tersebut. |
| [getTargetSlide()](#getTargetSlide--) | Jika HyperlinkEx menargetkan slide tertentu, mengembalikan slide ini. |
| [getTargetFrame()](#getTargetFrame--) | Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk bila ada. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk bila ada. |
| [getTooltip()](#getTooltip--) | Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. |
| [getHistory()](#getHistory--) | Menentukan apakah target hyperlink induk akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. |
| [setHistory(boolean value)](#setHistory-boolean-) | Menentukan apakah target hyperlink induk akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. |
| [getHighlightClick()](#getHighlightClick--) | Menentukan apakah hyperlink harus disorot saat diklik. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Menentukan apakah hyperlink harus disorot saat diklik. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Menentukan apakah suara harus dihentikan saat hyperlink diklik. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Menentukan apakah suara harus dihentikan saat hyperlink diklik. |
| [getSound()](#getSound--) | Mewakili suara yang diputar dari hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Mewakili suara yang diputar dari hyperlink. |
| [getColorSource()](#getColorSource--) | Mewakili sumber warna hyperlink - baik gaya atau format bagian. |
| [setColorSource(int value)](#setColorSource-int-) | Mewakili sumber warna hyperlink - baik gaya atau format bagian. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Menentukan apakah dua instance Hyperlink sama. |

PowerPoint memiliki perilaku khusus untuk tautan dan teks yang bersesuaian dalam sebuah bagian. Ini memungkinkan membuat teks untuk hyperlink dalam bentuk URL yang valid, berbeda dari alamat sebenarnya dari tautan. Dalam kasus ini, ketika Anda melihat tautan di jendela edit, itu akan diubah agar sesuai dengan bagian teks. Properti ini mewakili nilai asli dari hyperlink.

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Mengembalikan tipe aksi HyperLinkEx. Hanya-baca [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Mengembalikan:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Menentukan URL eksternal. Jika properti ini menjadi tidak null maka properti TargetSlide menjadi null. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Mewakili sebuah hyperlink yang ditetapkan untuk bagian ini tanpa memperhatikan konten sebenarnya dari bagian tersebut.

**Mengembalikan:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Jika HyperlinkEx menargetkan slide tertentu, mengembalikan slide ini. Jika properti ini menjadi tidak null maka properti ExternalUrl menjadi null. Hanya-baca [ISlide](../../com.aspose.slides/islide).

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk bila ada. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk bila ada. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Menentukan apakah target hyperlink induk akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Menentukan apakah target hyperlink induk akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Menentukan apakah hyperlink harus disorot saat diklik. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Menentukan apakah hyperlink harus disorot saat diklik. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Menentukan apakah suara harus dihentikan saat hyperlink diklik. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Menentukan apakah suara harus dihentikan saat hyperlink diklik. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Mewakili suara yang diputar dari hyperlink. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Dapatkan hyperlink bentuk pertama
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Ekstrak suara hyperlink dalam array byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Mewakili suara yang diputar dari hyperlink. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Dapatkan hyperlink bentuk pertama
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Ekstrak suara hyperlink dalam array byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Mewakili sumber warna hyperlink - baik gaya atau format bagian. Baca/tulis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Mengembalikan:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Mewakili sumber warna hyperlink - baik gaya atau format bagian. Baca/tulis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Menentukan apakah dua instance Hyperlink sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink untuk dibandingkan dengan Hyperlink saat ini. |
**Mengembalikan:**
boolean - **true** jika Hyperlink yang ditentukan sama dengan Hyperlink saat ini; otherwise, **false**.