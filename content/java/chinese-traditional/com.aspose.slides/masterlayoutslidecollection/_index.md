---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides for Java API 參考
description: 表示已定義母版投影片的所有版面投影片集合。
type: docs
url: /zh-hant/com.aspose.slides/masterlayoutslidecollection/
---
**繼承:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**所有已實作的介面:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

表示已定義母版投影片的所有版面投影片集合。擴充 LayoutSlideCollection 類別，提供在母版的各個版面投影片集合上下文中新增/插入/移除/複製/重新排序版面投影片的方法。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 將指定版面投影片的副本新增至集合的末端。 |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | 將指定版面投影片的副本插入至集合的指定位置。 |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | 將新的版面投影片新增至集合的末端。 |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | 將新的版面投影片插入至集合的指定位置。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引的元素。 |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | 將版面投影片從集合移動至指定位置。 |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

將指定版面投影片的副本新增至集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要複製的投影片。 |

--------------------

1) 新的版面將與此版面投影片集合的母版投影片連結。因此這相當於在 PowerPoint 中使用「使用目標佈景主題」選項的複製/貼上。 2) 此方法的類似方法是 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-)，透過 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 屬性存取。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

將指定版面投影片的副本插入至集合的指定位置。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要複製的投影片。 |

--------------------

新的版面將與此版面投影片集合的母版投影片連結。因此這相當於在 PowerPoint 中使用「使用目標佈景主題」選項的複製/貼上。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已插入的投影片。
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

將新的版面投影片新增至集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| layoutType | byte | 新版面的版面類型。支援的版面類型有：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。現在不支援的版面類型有：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新版面的名稱。若傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null，則會根據傳入的版面類型自動產生名稱（例如 "Title Slide" 或 "1\_Title Slide", "2\_..", 等）。 |

--------------------

1) 當 layoutType 為 SlideLayoutType.Custom 時，新增的版面不包含任何版位標記與圖形。 2) 此方法的類似方法是 [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-)，透過 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 屬性存取。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

將新的版面投影片插入至集合的指定位置。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| layoutType | byte | 新版面的版面類型。支援的版面類型有：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。現在不支援的版面類型有：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新版面的名稱。若傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null，則會根據傳入的版面類型自動產生名稱（例如 "Title Slide" 或 "1\_Title Slide", "2\_..", 等）。 |

--------------------

當 layoutType 為 SlideLayoutType.Custom 時，插入的版面不包含任何版位標記與圖形。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已插入的投影片。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

--------------------

1) 為避免拋出 PptxEditException，請先檢查版面的 HasDependingSlides 屬性。 2) 您也可以使用 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 方法來簡化程式碼。

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

將版面投影片從集合移動至指定位置。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 目標索引。 |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要移動的投影片。 |