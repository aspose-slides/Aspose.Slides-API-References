---
title: Hyperlink
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebuah hyperlink.
type: docs
url: /id/com.aspose.slides/hyperlink/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Mewakili sebuah hyperlink.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Membuat sebuah instance dari hyperlink. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Membuat sebuah instance dari hyperlink yang menunjuk ke slide tertentu. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Membuat sebuah instance dari hyperlink menggunakan hyperlink lain sebagai sumber, menimpa properti sekunder. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Mengembalikan hyperlink khusus "do nothing". |
| [getMedia()](#getMedia--) | Mengembalikan hyperlink khusus "play mediafile". |
| [getNextSlide()](#getNextSlide--) | Mengembalikan hyperlink ke slide berikutnya. |
| [getPreviousSlide()](#getPreviousSlide--) | Mengembalikan hyperlink ke slide sebelumnya. |
| [getFirstSlide()](#getFirstSlide--) | Mengembalikan hyperlink ke slide pertama dalam presentasi. |
| [getLastSlide()](#getLastSlide--) | Mengembalikan hyperlink ke slide terakhir dalam presentasi. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Mengembalikan hyperlink ke slide yang terakhir dilihat. |
| [getEndShow()](#getEndShow--) | Mengembalikan hyperlink yang mengakhiri pertunjukan. |
| [getActionType()](#getActionType--) | Mengembalikan tipe aksi Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | Menentukan URL eksternal. |
| [getTargetSlide()](#getTargetSlide--) | Jika Hyperlink menarget slide tertentu, mengembalikan slide tersebut. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Mewakili hyperlink yang ditetapkan untuk bagian ini tanpa memperhatikan konten aktual bagian tersebut. |
| [getTargetFrame()](#getTargetFrame--) | Mengembalikan frame dalam parent HTML frameset untuk target hyperlink parent ketika ada. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Mengembalikan frame dalam parent HTML frameset untuk target hyperlink parent ketika ada. |
| [getTooltip()](#getTooltip--) | Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink parent. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink parent. |
| [getHistory()](#getHistory--) | Menentukan apakah target hyperlink parent akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. |
| [setHistory(boolean value)](#setHistory-boolean-) | Menentukan apakah target hyperlink parent akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. |
| [getHighlightClick()](#getHighlightClick--) | Menentukan apakah hyperlink harus disorot saat diklik. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Menentukan apakah hyperlink harus disorot saat diklik. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Menentukan apakah suara harus dihentikan saat hyperlink diklik. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Menentukan apakah suara harus dihentikan saat hyperlink diklik. |
| [getSound()](#getSound--) | Mewakili suara yang diputar oleh hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Mewakili suara yang diputar oleh hyperlink. |
| [getColorSource()](#getColorSource--) | Mewakili sumber warna hyperlink – baik style maupun format bagian. |
| [setColorSource(int value)](#setColorSource-int-) | Mewakili sumber warna hyperlink – baik style maupun format bagian. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua instance Hyperlink sama. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Menentukan apakah dua instance Hyperlink sama. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Menguji dua hyperlink untuk kesamaan. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Menguji dua hyperlink untuk ketidaksamaan. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk algoritma hashing dan struktur data seperti hash table. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Membuat sebuah instance dari hyperlink.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL hyperlink. |
### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Membuat sebuah instance dari hyperlink yang menunjuk ke slide tertentu. Catatan: hyperlink yang dibuat harus ditetapkan ke objek dari presentasi yang sama, jika tidak tautan akan disimpan sebagai NoAction.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide target. |
### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Membuat sebuah instance dari hyperlink menggunakan hyperlink lain sebagai sumber, menimpa properti sekunder.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink sumber |
| targetFrame | java.lang.String | Frame target |
| tooltip | java.lang.String | Teks tooltip |
| history | boolean | Menentukan apakah target hyperlink parent akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. |
| stopSoundsOnClick | boolean | Menentukan apakah suara harus dihentikan saat hyperlink diklik. |
| highlightClick | boolean | Menentukan apakah hyperlink harus disorot saat diklik. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Mengembalikan hyperlink khusus "do nothing". Hanya-baca [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Mengembalikan hyperlink khusus "play mediafile". Digunakan pada AudioFrame dan VideoFrame. Hanya-baca [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Mengembalikan hyperlink ke slide berikutnya. Hanya-baca [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Mengembalikan hyperlink ke slide sebelumnya. Hanya-baca [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Mengembalikan hyperlink ke slide pertama dalam presentasi. Hanya-baca [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Mengembalikan hyperlink ke slide terakhir dalam presentasi. Hanya-baca [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Mengembalikan hyperlink ke slide yang terakhir dilihat. Hanya-baca [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Mengembalikan hyperlink yang mengakhiri pertunjukan. Hanya-baca [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Mengembalikan tipe aksi Hyperlink. Hanya-baca [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Mengembalikan:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Menentukan URL eksternal. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Jika Hyperlink menarget slide tertentu, mengembalikan slide tersebut. Hanya-baca [ISlide](../../com.aspose.slides/islide).

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Mewakili hyperlink yang ditetapkan untuk bagian ini tanpa memperhatikan konten aktual bagian tersebut.

--------------------

PowerPoint memperlakukan tautan dan teks yang terkait dalam sebuah bagian secara khusus. Itu memungkinkan pembuatan teks untuk hyperlink dalam bentuk URL yang valid, berbeda dari alamat sebenarnya dari tautan. Dalam hal ini, ketika Anda melihat tautan di jendela edit, akan diubah agar sesuai dengan bagian teks. Properti ini mewakili nilai asli dari hyperlink.

**Mengembalikan:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Mengembalikan frame dalam parent HTML frameset untuk target hyperlink parent ketika ada. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Mengembalikan frame dalam parent HTML frameset untuk target hyperlink parent ketika ada. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink parent. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Mengembalikan string yang dapat ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink parent. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Menentukan apakah target hyperlink parent akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Menentukan apakah target hyperlink parent akan ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Menentukan apakah hyperlink harus disorot saat diklik. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Menentukan apakah hyperlink harus disorot saat diklik. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Menentukan apakah suara harus dihentikan saat hyperlink diklik. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Menentukan apakah suara harus dihentikan saat hyperlink diklik. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Mewakili suara yang diputar oleh hyperlink. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Dapatkan hyperlink shape pertama
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
public final void setSound(IAudio value)
```

Mewakili suara yang diputar oleh hyperlink. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Dapatkan hyperlink shape pertama
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
public final int getColorSource()
```

Mewakili sumber warna hyperlink – baik style maupun format bagian. Baca/tulis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Mengembalikan:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Mewakili sumber warna hyperlink – baik style maupun format bagian. Baca/tulis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah dua instance Hyperlink sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Hyperlink yang dibandingkan dengan Hyperlink saat ini. |

**Mengembalikan:**
boolean - **true** jika Hyperlink yang ditentukan sama dengan Hyperlink saat ini; lainnya, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Menentukan apakah dua instance Hyperlink sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink yang dibandingkan dengan Hyperlink saat ini. |

**Mengembalikan:**
boolean - **true** jika Hyperlink yang ditentukan sama dengan Hyperlink saat ini; lainnya, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Menguji dua hyperlink untuk kesamaan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink pertama yang diuji. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink kedua yang diuji. |

**Mengembalikan:**
boolean - **true** jika hyperlink sama.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Menguji dua hyperlink untuk ketidaksamaan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink pertama yang diuji. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink kedua yang diuji. |

**Mengembalikan:**
boolean - **false** jika hyperlink sama.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk algoritma hashing dan struktur data seperti hash table.

**Mengembalikan:**
int - Kode hash untuk sebuah URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject