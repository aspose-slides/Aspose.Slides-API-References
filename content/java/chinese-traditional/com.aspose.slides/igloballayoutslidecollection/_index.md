---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides for Java API 參考
description: 代表簡報中所有版面投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/igloballayoutslidecollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

代表簡報中所有版面投影片的集合。延伸 ILayoutSlideCollection 介面，提供在合併各個母片版面投影片集合時，新增/複製版面投影片的方法。

## Methods

| 方法 | 說明 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 將指定的版面投影片副本新增至簡報。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 將指定的版面投影片副本新增至簡報。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 在簡報中新增一個版面投影片。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

將指定的版面投影片副本新增至簡報。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要複製的投影片。 |

--------------------

在不同簡報之間複製版面時，亦可以同時複製版面的母片，以保留來源的格式。系統會使用內部註冊表自動追蹤已複製的母片，避免同一母片被多次複製。手動複製母片不會受到阻止，也不會被註冊。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

將指定的版面投影片副本新增至簡報。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要複製的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新版面的母片投影片。 |

--------------------

新版面會與目標簡報中指定的母片連結。這相當於 PowerPoint 中使用「使用目標佈景主題」選項的複製/貼上功能。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

在簡報中新增一個版面投影片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新版面的母片投影片。 |
| layoutType | byte | 新版面的版面類型。支援的版面類型包括：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。目前不支援的版面類型有：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新版面的名稱。若傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null，則會根據傳入的版面類型自動產生名稱（例如「Title Slide」或「1_Title Slide」、 「2_…」等）。 |

--------------------

1) 為 layoutType 為 LayoutSlideType.Custom 時，新增的版面不包含佔位符和圖形。2) 此方法的對應方法為 [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-)，可透過 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 屬性存取。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。