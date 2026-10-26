---
title: MasterLayoutSlideCollection
second_title: Aspose.Sildes 用于 PHP 的 Java API 参考
description: 
type: docs
url: /zh/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection 类

表示已定义母版幻灯片的所有布局幻灯片的集合。  
扩展 LayoutSlideCollection 类，提供在母版布局幻灯片各自集合上下文中添加/插入/删除/克隆/重新排序布局幻灯片的方法。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (byte, String) | 向集合末尾添加一个新的布局幻灯片。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| layoutType | byte | 用于新布局的布局类型。支持的布局类型有：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。当前不支持的布局类型有：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layoutName | String | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据传入的布局类型自动生成名称（例如 “Title Slide” 或 “1_Title Slide”、 “2_..” 等）。1) 对于布局类型为 SlideLayoutType.Custom 的值，添加的布局不包含占位符和形状。2) 此方法的对应方法是 IGlobalLayoutSlideCollection#add(IMasterSlide,byte,String)，通过 ( IPresentation#getLayoutSlides) 属性访问。 |

**返回值:**
[LayoutSlide](../layoutslide)

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.ArgumentException | 如果布局名称值 layoutName 已在此集合中使用，则抛出。 |

---

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([LayoutSlide](../layoutslide)) | 向集合末尾添加指定布局幻灯片的副本。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [LayoutSlide](../layoutslide) | 要克隆的幻灯片。1) 新布局将与此布局幻灯片集合的父母版幻灯片关联。因此这相当于在 PowerPoint 中使用“使用目标主题”选项的复制/粘贴。2) 此方法的对应方法是 IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide)，通过 ( IPresentation#getLayoutSlides) 属性访问。 |

**返回值:**
[LayoutSlide](../layoutslide)

---

### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, byte, String) | 在集合的指定位置插入一个新的布局幻灯片。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| layoutType | byte | 用于新布局的布局类型。支持的布局类型有：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。当前不支持的布局类型有：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layoutName | String | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。如果传入 null 参数，则会根据传入的布局类型自动生成名称（例如 “Title Slide” 或 “1_Title Slide”、 “2_..” 等）。对值为 SlideLayoutType.Custom 的布局类型，插入的布局不包含占位符和形状。 |

**返回值:**
[LayoutSlide](../layoutslide)

**异常**

| 错误 | 条件 |
| --- | --- |
| com.aspose.ms.System.ArgumentException | 如果布局名称值 layoutName 已在此集合中使用，则抛出。 |

---

### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [LayoutSlide](../layoutslide)) | 在集合的指定位置插入指定布局幻灯片的副本。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceLayout | [LayoutSlide](../layoutslide) | 要克隆的幻灯片。新布局将与此布局幻灯片集合的父母版幻灯片关联。 |

**返回值:**
[LayoutSlide](../layoutslide)

---

### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 删除集合中指定索引的元素。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的元素的零基索引。1) 为避免抛出 PptxEditException，请在此之前检查布局的 HasDependingSlides 属性。2) 也可以使用 ILayoutSlide#remove 方法简化代码。 |

**返回值:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 如果布局在演示文稿中被使用（其 HasDependingSlides 属性为 true），则抛出。 |

---

### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [LayoutSlide](../layoutslide)) | 将布局幻灯片从集合中移动到指定位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 目标索引。 |
| layoutSlide | [LayoutSlide](../layoutslide) | 要移动的幻灯片。 |

**返回值:**
void