---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示簡報中所有版面投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/globallayoutslidecollection/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**所有已實作介面:**  
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)  
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

表示簡報中所有版面投影片的集合。繼承 LayoutSlideCollection 類別，提供在合併主版面投影片的各個集合時，新增/複製版面投影片的方法。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 將指定的版面投影片複製新增至簡報。 |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 將指定的版面投影片複製新增至簡報。 |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 在簡報中新增一個版面投影片。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

將指定的版面投影片複製新增至簡報。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的投影片。 |

--------------------

在不同簡報之間克隆版面時，版面的母片也可以一起克隆，以保留來源的格式。系統會使用內部註冊表自動追蹤已克隆的母片，防止同一母片產生多個克隆。手動克隆母片不會受到阻止，也不會被註冊。 |

**傳回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

將指定的版面投影片複製新增至簡報。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的投影片。 |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 新版面的母片投影片。 |

--------------------

1) 新版面將與目標簡報中指定的母片連結。因此相當於在 PowerPoint 中使用「使用目標佈景主題」選項的複製/貼上。2) 此方法的對應方法是 [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-)，可透過 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 屬性存取。 |

**傳回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

在簡報中新增一個版面投影片。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 用於新版面的母片投影片。 |
| layoutType | byte | 新版面的版面類型。支援的版面類型包括：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。其他目前不支援的版面類型有：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新版面的名稱。若傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null，則會自動根據傳入的版面類型產生名稱（例如「Title Slide」或「1_Title Slide」、「2_..」等）。 |

--------------------

1) 當 layoutType 為 SlideLayoutType.Custom 時，新增的版面不含任何佔位符與圖形。2) 此方法的對應方法是 [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-)，可透過 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 屬性存取。 |

**傳回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。