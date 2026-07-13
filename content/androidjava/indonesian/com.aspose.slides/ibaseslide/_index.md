---
title: IBaseSlide
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili data umum untuk semua jenis slide.
type: docs
url: /id/com.aspose.slides/ibaseslide/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Mewakili data umum untuk semua jenis slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShapes()](#getShapes--) | Mengembalikan bentuk-bentuk slide. |
| [getControls()](#getControls--) | Mengembalikan koleksi kontrol ActiveX pada slide. |
| [getName()](#getName--) | Mengembalikan atau mengatur nama slide. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan atau mengatur nama slide. |
| [getSlideId()](#getSlideId--) | Mengembalikan ID slide. |
| [getCustomData()](#getCustomData--) | Mengembalikan data khusus slide. |
| [getTimeline()](#getTimeline--) | Mengembalikan objek timeline animasi. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Mengembalikan objek TransitionEx yang berisi informasi tentang cara slide yang ditentukan beralih selama pertunjukan slide. |
| [getBackground()](#getBackground--) | Mengembalikan latar belakang slide. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Menyediakan akses mudah ke hyperlink yang terkandung. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Menemukan kemunculan pertama bentuk dengan teks alternatif yang ditentukan. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan format yang sama di semua paragraf dalam semua bentuk yang dapat diterima. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Menentukan apakah dua instance IBaseSlide sama. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


Mengembalikan bentuk-bentuk slide. Baca-saja [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Mengembalikan:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


Mengembalikan koleksi kontrol ActiveX pada slide. Baca-saja [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Mengembalikan:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


Mengembalikan atau mengatur nama slide. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Mengembalikan atau mengatur nama slide. Baca/tulis String.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


Mengembalikan ID slide. Baca-saja long.

**Mengembalikan:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Mengembalikan data khusus slide. Baca-saja [ICustomData](../../com.aspose.slides/icustomdata).

**Mengembalikan:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


Mengembalikan objek timeline animasi. Baca-saja [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Mengembalikan:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


Mengembalikan objek TransitionEx yang berisi informasi tentang cara slide yang ditentukan beralih selama pertunjukan slide. Baca-saja [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Mengembalikan:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


Mengembalikan latar belakang slide. Baca-saja [IBackground](../../com.aspose.slides/ibackground).

**Mengembalikan:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Menediakan akses mudah ke hyperlink yang terkandung. Baca-saja [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Mengembalikan:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


Menemukan kemunculan pertama bentuk dengan teks alternatif yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| altText | java.lang.String | Teks alternatif. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - objek ShapeEx atau null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Menggabungkan run dengan format yang sama di semua paragraf dalam semua bentuk yang dapat diterima.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


Menentukan apakah dua instance IBaseSlide sama. Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis. Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll. sama. Perbandingan tidak memperhitungkan nilai identifier unik, misalnya SlideId, serta konten dinamis, misalnya nilai tanggal saat ini pada Placeholder Tanggal.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide yang dibandingkan dengan IBaseSlide saat ini. |

**Mengembalikan:**
boolean - **true** jika IBaseSlide yang ditentukan sama dengan IBaseSlide saat ini; sebaliknya, **false**.