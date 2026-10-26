---
title: BaseSlide
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili data umum untuk semua tipe slide.
type: docs
url: /id/com.aspose.slides/baseslide/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Mewakili data umum untuk semua tipe slide.
## Metode

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Mengembalikan bentuk-bentuk pada slide. |
| [getControls()](#getControls--) | Mengembalikan koleksi kontrol ActiveX pada slide. |
| [getName()](#getName--) | Mengembalikan atau mengatur nama slide. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan atau mengatur nama slide. |
| [getSlideId()](#getSlideId--) | Mengembalikan ID slide. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Menentukan apakah dua instance IBaseSlide sama. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan pemformatan yang sama di semua paragraf pada semua bentuk yang dapat diterima. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Menggabungkan run dengan pemformatan yang sama di semua paragraf pada semua bentuk yang dapat diterima. |
| [createThemeEffective()](#createThemeEffective--) | Mengembalikan tema efektif untuk slide ini. |
| [getCustomData()](#getCustomData--) | Mengembalikan data kustom slide. |
| [getTimeline()](#getTimeline--) | Mengembalikan objek timeline animasi. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Mengembalikan objek Transition yang berisi informasi tentang bagaimana slide yang ditentukan maju selama pertunjukan slide. |
| [getBackground()](#getBackground--) | Mengembalikan latar belakang slide. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Menyediakan akses mudah ke hyperlink yang terkandung. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Menemukan kemunculan pertama bentuk dengan teks alternatif yang ditentukan. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Mengembalikan antarmuka IPresentation. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Mengembalikan bentuk-bentuk pada slide. Baca-saja [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Mengembalikan:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Mengembalikan koleksi kontrol ActiveX pada slide. Baca-saja [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Mengembalikan:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Mengembalikan atau mengatur nama slide. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Mengembalikan atau mengatur nama slide. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Mengembalikan ID slide. Baca-saja long.

**Mengembalikan:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Menentukan apakah dua instance IBaseSlide sama. Nilai kembali dihitung berdasarkan struktur slide dan konten statis. Dua slide sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll. sama. Perbandingan tidak mempertimbangkan nilai pengenal unik, misalnya SlideId, serta konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide yang dibandingkan dengan IBaseSlide saat ini. |

**Mengembalikan:**
boolean -  **true**  jika IBaseSlide yang ditentukan sama dengan IBaseSlide saat ini; lainnya,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Menggabungkan run dengan pemformatan yang sama di semua paragraf pada semua bentuk yang dapat diterima.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Menggabungkan run dengan pemformatan yang sama di semua paragraf pada semua bentuk yang dapat diterima.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Mengembalikan tema efektif untuk slide ini.

**Mengembalikan:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Mengembalikan data kustom slide. Baca-saja [ICustomData](../../com.aspose.slides/icustomdata).

**Mengembalikan:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Mengembalikan objek timeline animasi. Baca-saja [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Mengembalikan:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Mengembalikan objek Transition yang berisi informasi tentang bagaimana slide yang ditentukan maju selama pertunjukan slide. Baca-saja [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Mengembalikan:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Mengembalikan latar belakang slide. Baca-saja [IBackground](../../com.aspose.slides/ibackground).

**Mengembalikan:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Menyediakan akses mudah ke hyperlink yang terkandung. Baca-saja [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Mengembalikan:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Menemukan kemunculan pertama bentuk dengan teks alternatif yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| altText | java.lang.String | Teks alternatif. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - objek Shape atau null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan antarmuka IPresentation. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide dasar. Baca-saja [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)