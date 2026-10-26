---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表已定義母片的所有版面投影片的集合。
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

代表已定義母片的所有版面投影片的集合。繼承 LayoutSlideCollection 類別，提供在母片的版面投影片各自集合中新增/插入/移除/複製/重新排序版面投影片的方法。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 將指定版面投影片的副本新增至集合的末端。 |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | 在集合中指定位置插入指定版面投影片的副本。 |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | 新增一個版面投影片至集合的末端。 |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | 在集合中指定位置插入新的版面投影片。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引的元素。 |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | 將版面投影片從集合中移動到指定位置。 |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

將指定版面投影片的副本新增至集合的末端。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的投影片。 |

--------------------

1) 新版面將與此版面投影片集合的父母片連結。等同於在 PowerPoint 中使用「使用目標主題」的複製/貼上。  
2) 此方法的等價方式是使用 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 方法，透過 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 屬性存取。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

在集合中指定位置插入指定版面投影片的副本。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要克隆的投影片。 |

--------------------

新版面將與此版面投影片集合的父母片連結。等同於在 PowerPoint 中使用「使用目標主題」的複製/貼上。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已插入的投影片。

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

在集合的末端新增一個版面投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| layoutType | byte | 新版面的版面類型。支援的版面類型：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。暫不支援的版面類型包括：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新版面的名稱。如果傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null，系統會根據傳入的 layoutType 自動產生名稱（例如 "Title Slide"、"1\_Title Slide"、"2\_.." 等）。 |

--------------------

1) 為 SlideLayoutType.Custom 的 layoutType 新增的版面不包含佔位符與圖形。  
2) 此方法的等價方式是使用 [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) 方法，透過 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 屬性存取。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已新增的投影片。

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

在集合中指定位置插入新的版面投影片。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| layoutType | byte | 新版面的版面類型。支援的版面類型：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。暫不支援的版面類型包括：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layoutName | java.lang.String | 新版面的名稱。如果傳入的名稱已被使用，將拋出 ArgumentException。若傳入 null，系統會根據傳入的 layoutType 自動產生名稱（例如 "Title Slide"、"1\_Title Slide"、"2\_.." 等）。 |

--------------------

為 SlideLayoutType.Custom 的 layoutType 插入的版面不包含佔位符與圖形。

**傳回值:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 已插入的投影片。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引的元素。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

--------------------

1) 為避免拋出 PptxEditException，請先檢查版面的 HasDependingSlides 屬性。  
2) 您也可以使用 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 方法來簡化程式碼。

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

將版面投影片從集合中移動到指定位置。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 目標索引。 |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要移動的投影片。 |