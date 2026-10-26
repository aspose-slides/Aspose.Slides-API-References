---
title: BaseSlide
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili data umum untuk semua jenis slide.
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

Mewakili data umum untuk semua jenis slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShapes()](#getShapes--) | Mengembalikan shape pada slide. |
| [getControls()](#getControls--) | Mengembalikan koleksi kontrol ActiveX pada slide. |
| [getName()](#getName--) | Mengembalikan atau mengatur nama slide. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan atau mengatur nama slide. |
| [getSlideId()](#getSlideId--) | Mengembalikan ID slide. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Menentukan apakah dua instance IBaseSlide sama. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan format yang sama di semua paragraf pada semua shape yang dapat diterima. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Menggabungkan run dengan format yang sama di semua paragraf pada semua shape yang dapat diterima. |
| [createThemeEffective()](#createThemeEffective--) | Mengembalikan tema efektif untuk slide ini. |
| [getCustomData()](#getCustomData--) | Mengembalikan data khusus slide. |
| [getTimeline()](#getTimeline--) | Mengembalikan objek timeline animasi. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Mengembalikan objek Transition yang berisi informasi tentang bagaimana slide yang ditentukan maju selama pertunjukan slide. |
| [getBackground()](#getBackground--) | Mengembalikan latar belakang slide. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Menyediakan akses mudah ke hyperlink yang terkandung. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Menemukan kemunculan pertama sebuah shape dengan teks alternatif yang ditentukan. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Mengembalikan antarmuka IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Mengembalikan shape pada slide. Hanya-baca [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Mengembalikan:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Mengembalikan koleksi kontrol ActiveX pada slide. Hanya-baca [IControlCollection](../../com.aspose.slides/icontrolcollection).

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

Mengembalikan ID slide. Hanya-baca long.

**Mengembalikan:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Menentukan apakah dua instance IBaseSlide sama. Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis. Dua slide dianggap sama jika semua shape, style, teks, animasi, dan pengaturan lain, dll. sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId, dan konten dinamis, misalnya nilai tanggal saat ini dalam Date Placeholder.

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
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide untuk dibandingkan dengan IBaseSlide saat ini. |

**Mengembalikan:**
boolean -  **true**  jika IBaseSlide yang ditentukan sama dengan IBaseSlide saat ini; sebaliknya,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Menggabungkan run dengan format yang sama di semua paragraf pada semua shape yang dapat diterima.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Menggabungkan run dengan format yang sama di semua paragraf pada semua shape yang dapat diterima.

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

Mengembalikan data khusus slide. Hanya-baca [ICustomData](../../com.aspose.slides/icustomdata).

**Mengembalikan:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Mengembalikan objek timeline animasi. Hanya-baca [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Mengembalikan:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Mengembalikan objek Transition yang berisi informasi tentang bagaimana slide yang ditentukan maju selama pertunjukan slide. Hanya-baca [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Mengembalikan:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Mengembalikan latar belakang slide. Hanya-baca [IBackground](../../com.aspose.slides/ibackground).

**Mengembalikan:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Menyediakan akses mudah ke hyperlink yang terkandung. Hanya-baca [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Mengembalikan:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Menemukan kemunculan pertama sebuah shape dengan teks alternatif yang ditentukan.

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

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan antarmuka IPresentation. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide dasar. Hanya-baca [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)