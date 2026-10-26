---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示簡報中所有版面投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/globallayoutslidecollection/
---
**繼承：**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**所有已實作的介面：**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

表示簡報中所有版面投影片的集合。繼承 LayoutSlideCollection 類，提供在合併各個主版面投影片集合的情境下，新增/複製版面投影片的方法。
## 方法

| Method | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 將指定的版面投影片複製新增至簡報中。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 將指定的版面投影片複製新增至簡報中。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 在簡報中新增一個版面投影片。 |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

將指定的版面投影片複製新增至簡報中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要複製的投影片。 |

--------------------

在不同簡報之間複製版面時，亦可複製版面的母片以保留來源格式。內部註冊表用於追蹤自動複製的母片，防止同一母片投影片產生多個副本。手動複製母片投影片既不會被阻止，也不會被註冊。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

將指定的版面投影片複製新增至簡報中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要複製的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新版面的母片投影片。 |

--------------------

1) 新的版面將會在目標簡報中與指定的母片連結。這相當於在 PowerPoint 中使用「使用目的地主題」選項的複製/貼上。2) 此方法的類似方法是 [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-)，可透過 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 屬性存取。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

將新版面投影片新增至簡報中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新版面的母片投影片。 |
| layoutType | byte | 新版面的版面類型。支援的版面類型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。其他版面類型目前不支援：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新版面的名稱。若提供的名稱已被使用，將拋出 ArgumentException。若傳入 null，則會根據提供的 layout type 自動產生名稱（例如「Title Slide」或「1\_Title Slide」、「2\_..」等）。 |

--------------------

1) 當 layoutType 為 SlideLayoutType.Custom 時，新增的版面不包含任何佔位符或圖形。2) 此方法的類似方法是 [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-)，可透過 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 屬性存取。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。