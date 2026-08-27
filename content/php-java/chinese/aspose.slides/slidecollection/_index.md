---
title: SlideCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/slidecollection/
---
## SlideCollection 类

 表示一个幻灯片的集合。

### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Slide](../slide)) | 将指定幻灯片的副本添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | 要克隆的幻灯片。当在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要对克隆过程进行更细粒度的控制，请使用 #addClone(ISlide,ILayoutSlide) 或 #addClone(ISlide,IMasterSlide,boolean) 来克隆幻灯片，IGlobalLayoutSlideCollection#addClone(ILayoutSlide) 或 IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) 来克隆布局，以及 IMasterSlideCollection#addClone(IMasterSlide) 来克隆母版。 |

**返回值：**
[Slide](../slide)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Slide](../slide), [Section](../section)) | 将指定幻灯片的副本添加到指定章节的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | 要克隆的幻灯片。 |
| section | [Section](../section) | 新幻灯片所在的章节。 |

**返回值：**
[Slide](../slide)

**异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 当 section 参数包含错误或无效值时。 |

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Slide](../slide), [LayoutSlide](../layoutslide)) | 将指定幻灯片的副本添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | 要克隆的幻灯片。 |
| destLayout | [LayoutSlide](../layoutslide) | 新幻灯片的布局幻灯片。 |

**返回值：**
[Slide](../slide)

---


### addClone {#addClone}

| 名称 | 描述 |
| --- | --- |
| addClone ([Slide](../slide), [MasterSlide](../masterslide), boolean) | 将指定源幻灯片的副本添加到集合的末尾。将自动从指定的母版中选择合适的布局（合适的布局是与源幻灯片布局具有相同 Type 或 Name 的布局）。如果在指定的母版中没有合适的布局，则会克隆源幻灯片的布局（当 allowCloneMissingLayout 为 true 时）或抛出 PptxEditException（当 allowCloneMissingLayout 为 false 时）。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | 要克隆的幻灯片。当在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要对克隆过程进行更细粒度的控制，请使用 #addClone(ISlide,ILayoutSlide) 或 #addClone(ISlide,IMasterSlide,boolean) 来克隆幻灯片，IGlobalLayoutSlideCollection#addClone(ILayoutSlide) 或 IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) 来克隆布局，以及 IMasterSlideCollection#addClone(IMasterSlide) 来克隆母版。 |
| destMaster | [MasterSlide](../masterslide) | 新幻灯片的母版幻灯片。 |
| allowCloneMissingLayout | boolean | 如果在指定的母版中没有合适的布局，则会克隆源幻灯片的布局（当 allowCloneMissingLayout 为 true 时）或抛出 PptxEditException（当 allowCloneMissingLayout 为 false 时）。 |

**返回值：**
[Slide](../slide)

**异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 当在指定的母版中没有合适的布局且 allowCloneMissingLayout 为 false 时抛出。 |

---


### addEmptySlide {#addEmptySlide}

| 名称 | 描述 |
| --- | --- |
| addEmptySlide ([LayoutSlide](../layoutslide)) | 在集合的末尾添加一个新的空幻灯片。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| layout | [LayoutSlide](../layoutslide) | 幻灯片的布局。 |

**返回值：**
[Slide](../slide)

---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | String | Html 要添加的内容。 |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回值：**
[Slide](../slide)

---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | String | Html 要添加的内容。 |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回值：**
[Slide](../slide)

---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (String) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| htmlText | String | Html 要添加的内容。 |

**返回值：**
[Slide](../slide)

---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (InputStream, [HtmlExternalResolver](../htmlexternalresolver), String) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | InputStream | 将用作 HTML 文件来源的 Stream 对象。 |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回值：**
[Slide](../slide)

---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (InputStream, [ExternalResourceResolver](../externalresourceresolver), String) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | InputStream | 将用作 HTML 文件来源的 Stream 对象。 |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，将忽略所有外部对象。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回值：**
[Slide](../slide)

---


### addFromHtml {#addFromHtml}

| 名称 | 描述 |
| --- | --- |
| addFromHtml (InputStream) | 从 HTML 文本创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| htmlStream | InputStream | 将用作 HTML 文件来源的 Stream 对象。 |

**返回值：**
[Slide](../slide)

---


### addFromPdf {#addFromPdf}

| 名称 | 描述 |
| --- | --- |
| addFromPdf (String) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| path | String | PDF 文档的路径 |

**返回值：**
[Slide](../slide)

---


### addFromPdf {#addFromPdf}

| 名称 | 描述 |
| --- | --- |
| addFromPdf (String, [PdfImportOptions](../pdfimportoptions)) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾，考虑 pdf 导入选项。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| path | String | PDF 文档的路径 |
| pdfImportOptions | [PdfImportOptions](../pdfimportoptions) | pdf 导入选项 |

**返回值：**
[Slide](../slide)

---


### addFromPdf {#addFromPdf}

| 名称 | 描述 |
| --- | --- |
| addFromPdf (InputStream) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pdfStream | InputStream | 将用作 PDF 文档来源的流 |

**返回值：**
[Slide](../slide)

---


### addFromPdf {#addFromPdf}

| 名称 | 描述 |
| --- | --- |
| addFromPdf (InputStream, [PdfImportOptions](../pdfimportoptions)) | 从 PDF 文档创建幻灯片并将其添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pdfStream | InputStream | 将用作 PDF 文档来源的流 |
| pdfImportOptions | [PdfImportOptions](../pdfimportoptions) | pdf 导入选项 |

**返回值：**
[Slide](../slide)

---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

**返回值：**
Object

---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 Slide。 |

**返回值：**
[Slide](../slide)

---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([Slide](../slide)) | 返回集合中指定幻灯片的索引。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [Slide](../slide) | 要查找的幻灯片。 |

**返回值：**
int

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Slide](../slide)) | 将指定幻灯片的副本插入到集合的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [Slide](../slide) | 要克隆的幻灯片。当在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要对克隆过程进行更细粒度的控制，请使用 #insertClone(int,ISlide,ILayoutSlide) 或 #insertClone(int,ISlide,IMasterSlide,boolean) 来克隆幻灯片，以及 IMasterSlideCollection#addClone(IMasterSlide) 来克隆母版。 |

**返回值：**
[Slide](../slide)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Slide](../slide), [LayoutSlide](../layoutslide)) | 将指定幻灯片的副本插入到集合的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [Slide](../slide) | 要克隆的幻灯片。 |
| destLayout | [LayoutSlide](../layoutslide) | 新幻灯片的布局幻灯片。 |

**返回值：**
[Slide](../slide)

---


### insertClone {#insertClone}

| 名称 | 描述 |
| --- | --- |
| insertClone (int, [Slide](../slide), [MasterSlide](../masterslide), boolean) | 将指定源幻灯片的副本插入到集合的指定位置。将自动从指定的母版中选择合适的布局（合适的布局是与源幻灯片布局具有相同 Type 或 Name 的布局）。如果在指定的母版中没有合适的布局，则会克隆源幻灯片的布局（当 allowCloneMissingLayout 为 true 时）或抛出 PptxEditException（当 allowCloneMissingLayout 为 false 时）。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceSlide | [Slide](../slide) | 要克隆的幻灯片。 |
| destMaster | [MasterSlide](../masterslide) | 新幻灯片的母版幻灯片。 |
| allowCloneMissingLayout | boolean | 如果在指定的母版中没有合适的布局，则会克隆源幻灯片的布局（当 allowCloneMissingLayout 为 true 时）或抛出 PptxEditException（当 allowCloneMissingLayout 为 false 时）。 |

**返回值：**
[Slide](../slide)

**异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 当在指定的母版中没有合适的布局且 allowCloneMissingLayout 为 false 时抛出。 |

---


### insertEmptySlide {#insertEmptySlide}

| 名称 | 描述 |
| --- | --- |
| insertEmptySlide (int, [LayoutSlide](../layoutslide)) | 将指定幻灯片的副本插入到集合的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| layout | [LayoutSlide](../layoutslide) | 幻灯片的布局。 |

**返回值：**
[Slide](../slide)

---


### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, String, [HtmlExternalResolver](../htmlexternalresolver), String) | 从 HTML 文本创建幻灯片并将其插入到集合的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的位置。 |
| htmlText | String | Html 要添加的内容。 |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, String, [ExternalResourceResolver](../externalresourceresolver), String) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | String | 要添加的 Html。 |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, String, [HtmlExternalResolver](../htmlexternalresolver), String, boolean) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | String | 要添加的 Html。 |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果为 true，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果为 false，则数据将添加到新创建的幻灯片中。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, String, [ExternalResourceResolver](../externalresourceresolver), String, boolean) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | String | 要添加的 Html。 |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果为 true，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果为 false，则数据将添加到新创建的幻灯片中。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, String) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | String | 要添加的 Html。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, String, boolean) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlText | String | 要添加的 Html。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果为 true，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果为 false，则数据将添加到新创建的幻灯片中。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, InputStream, [HtmlExternalResolver](../htmlexternalresolver), String) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | InputStream | 用作 HTML 文件源的 Stream 对象。 |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, InputStream, [ExternalResourceResolver](../externalresourceresolver), String) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | InputStream | 用作 HTML 文件源的 Stream 对象。 |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, InputStream, [HtmlExternalResolver](../htmlexternalresolver), String, boolean) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | InputStream | 用作 HTML 文件源的 Stream 对象。 |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果为 true，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果为 false，则数据将添加到新创建的幻灯片中。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, InputStream, [ExternalResourceResolver](../externalresourceresolver), String, boolean) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | InputStream | 用作 HTML 文件源的 Stream 对象。 |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| uri | String | 指定 HTML 的 URI。用于解析相对链接。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果为 true，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果为 false，则数据将添加到新创建的幻灯片中。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, InputStream) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | InputStream | 用作 HTML 文件源的 Stream 对象。 |

**返回：**
[Slide](../slide)

---

### insertFromHtml {#insertFromHtml}

| 名称 | 描述 |
| --- | --- |
| insertFromHtml (int, InputStream, boolean) | 从 HTML 文本创建幻灯片并将其插入到集合中的指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入的位置。 |
| htmlStream | InputStream | 用作 HTML 文件源的 Stream 对象。 |
| useSlideWithIndexAsStart | boolean | 此标志决定插入的起始方式：从新幻灯片或从具有指定索引的幻灯片开始。如果为 true，则数据插入将从具有指定索引的幻灯片上的空白处开始。如果为 false，则数据将添加到新创建的幻灯片中。 |

**返回：**
[Slide](../slide)

---

### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。 |

**返回：**
boolean

---

### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

**返回：**



---

### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回：**



---

### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([Slide](../slide)) | 从集合中移除指定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [Slide](../slide) | 要从集合中移除的幻灯片。 |

**返回：**
void

---

### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 移除集合中指定索引处的元素。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 当 index 参数包含错误的节号时。 |

---

### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, [Slide](../slide)) | 将幻灯片从集合中移动到指定位置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 目标索引。 |
| slide | [Slide](../slide) | 要移动的幻灯片。 |

**返回：**
void

---

### reorder {#reorder}

| 名称 | 描述 |
| --- | --- |
| reorder (int, com.aspose.slides.ISlide[]) | 将幻灯片从集合中移动到指定位置。幻灯片将从 index 开始按照列表中出现的顺序放置。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 目标索引。 |
| slides | com.aspose.slides.ISlide[] | 要移动的幻灯片。 |

**返回：**
void

---

### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 获取集合实际包含的元素数量。只读 int。 |

**返回：**
int

---

### toArray {#toArray}

| 名称 | 描述 |
| --- | --- |
| toArray () | 创建并返回包含所有幻灯片的数组。 |

**返回：**
[Slide](../slide)

---

### toArray {#toArray}

| 名称 | 描述 |
| --- | --- |
| toArray (int, int) | 创建并返回包含指定范围内所有幻灯片的数组。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要添加的第一张幻灯片的索引。 |
| count | int | 要添加的幻灯片数量。 |

**返回：**
[Slide](../slide)

---