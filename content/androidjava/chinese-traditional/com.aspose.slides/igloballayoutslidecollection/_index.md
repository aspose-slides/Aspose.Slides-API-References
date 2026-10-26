---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示簡報中所有版面投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/igloballayoutslidecollection/
---
**所有已實作的介面：**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

表示簡報中所有版面投影片的集合。擴充 ILayoutSlideCollection 介面，提供在合併各個母片版面投影片集合的情境下加入/複製版面投影片的方法。

## 方法

| 方法 | 說明 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 將指定的版面投影片的副本新增至簡報。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 將指定的版面投影片的副本新增至簡報。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 在簡報中新增一個版面投影片。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

將指定的版面投影片的副本新增至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要複製的投影片。 |

當在不同簡報之間複製版面時，版面的母片亦可被複製以保留來源格式。內部登錄表用於追蹤自動複製的母片，防止同一母片投影片產生多個副本。手動複製母片投影片既不會被阻止，也不會被登錄。

**傳回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

將指定的版面投影片的副本新增至簡報。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要複製的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新版面的母片投影片。 |

新版面將與目標簡報中指定的母片連結。因此這相當於在 PowerPoint 中使用「使用目標主題」選項的複製/貼上。

**傳回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

在簡報中新增一個版面投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新版面的母片投影片。 |
| layoutType | byte | 新版面的版面類型。支援的版面類型包括：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。現在不支援的版面類型有：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新版面的名稱。如果傳入的名稱已被使用，將拋出 ArgumentException。如果傳入 null，則會根據傳入的版面類型自動產生名稱（例如 “Title Slide” 或 “1_Title Slide”、 “2_..” 等）。 |

1）對於 layoutType 為 SlideLayoutType.Custom 的值，新增的版面不包含佔位符和圖形。2）此方法的類似方式是透過屬性 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 存取的 [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) 方法。

**傳回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。