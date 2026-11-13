---
title: Presentation
second_title: Aspose.Slides for Java API 参考
description: 表示 Microsoft PowerPoint 演示文稿。
type: docs
url: /zh/com.aspose.slides/presentation/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject  
```
public final class Presentation implements IPresentation, IDOMObject
```

表示一个 Microsoft PowerPoint 演示文稿。

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // 实例化一个表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation();
>  try {
>      // 获取第一张幻灯片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 添加类型为线的自动形状
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // 保存演示文稿文件。
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // 在 Presentation 中加载任何受支持的文件，例如 ppt、pptx、odp 等。
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // 保存演示文稿文件。
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 构造函数

| Constructor | Description |
| --- | --- |
| [Presentation()](#Presentation--) | 此构造函数从头创建新的演示文稿。 |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | 此构造函数从头创建新的演示文稿。 |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | 此构造函数是读取现有 Presentation 的主要机制。 |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | 此构造函数是读取现有 Presentation 的主要机制。 |
| [Presentation(String file)](#Presentation-java.lang.String-) | 此构造函数获取用于读取 Presentation 内容的源文件路径。 |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | 此构造函数获取用于读取 Presentation 内容的源文件路径。 |
## 方法

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 返回或设置用于替代日期时间字段内容的日期和时间。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 返回或设置用于替代日期时间字段内容的日期和时间。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回实际的 HeaderFooter 管理器。 |
| [getProtectionManager()](#getProtectionManager--) | 获取此演示文稿的权限管理器。 |
| [getSlides()](#getSlides--) | 返回演示文稿中定义的所有幻灯片的列表。 |
| [getSections()](#getSections--) | 返回演示文稿中定义的所有幻灯片章节的列表。 |
| [getSlideSize()](#getSlideSize--) | 返回幻灯片尺寸对象。 |
| [getNotesSize()](#getNotesSize--) | 返回备注幻灯片尺寸对象。 |
| [getLayoutSlides()](#getLayoutSlides--) | 返回演示文稿中定义的所有布局幻灯片的列表。 |
| [getMasters()](#getMasters--) | 返回演示文稿中定义的所有母版幻灯片的列表。 |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | 返回备注母版管理器。 |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 返回讲义母版管理器。 |
| [getFontsManager()](#getFontsManager--) | 返回字体管理器。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | 返回形状的默认文本样式。 |
| [getCommentAuthors()](#getCommentAuthors--) | 返回评论作者的集合。 |
| [getDocumentProperties()](#getDocumentProperties--) | 返回包含标准和自定义文档属性的 DocumentProperties 对象。 |
| [getImages()](#getImages--) | 返回演示文稿中所有图像的集合。 |
| [getAudios()](#getAudios--) | 返回演示文稿中所有嵌入音频文件的集合。 |
| [getVideos()](#getVideos--) | 返回演示文稿中所有嵌入视频文件的集合。 |
| [getSlideShowSettings()](#getSlideShowSettings--) | 返回演示文稿的幻灯片放映设置。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | 返回用于签署演示文稿的签名集合。 |
| [getCustomData()](#getCustomData--) | 返回演示文稿的自定义数据。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 返回演示文稿中的所有自定义数据部分。 |
| [getVbaProject()](#getVbaProject--) | 获取或设置带有演示文稿宏的 VBA 项目。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 获取或设置带有演示文稿宏的 VBA 项目。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供对所有演示文稿幻灯片中包含的超链接的便捷访问（不包括母版、布局、备注幻灯片）。 |
| [getViewProperties()](#getViewProperties--) | 获取演示文稿范围的视图属性。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 表示演示文稿中的第一张幻灯片编号 |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 表示演示文稿中的第一张幻灯片编号 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 返回应用于演示文稿的敏感性标签集合。 |
| [getSlideById(long id)](#getSlideById-long-) | 通过 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |
| [getSourceFormat()](#getSourceFormat--) | 返回关于演示文稿从哪种格式加载的信息。 |
| [getMasterTheme()](#getMasterTheme--) | 返回母版主题。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 将演示文稿的所有幻灯片保存为指定格式的文件。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 将演示文稿的所有幻灯片保存到指定格式的流中。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加选项。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 将演示文稿的所有幻灯片保存到指定格式的流中，并使用附加选项。 |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 将演示文稿的所有幻灯片保存为表示 XAML 标记的一组文件。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 返回演示文稿所有幻灯片的 Image 对象。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 返回演示文稿指定幻灯片的缩略图 Image 对象。 |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 返回所有幻灯片的缩略图 Image 对象，使用自定义缩放。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 返回演示文稿指定幻灯片的缩略图 Image 对象，使用自定义缩放。 |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 返回所有幻灯片的缩略图 Image 对象，使用指定尺寸。 |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | 返回演示文稿指定幻灯片的缩略图 Image 对象，使用指定尺寸。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 将演示文稿的指定幻灯片保存为带有指定格式的文件，并保留页码。 |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 将演示文稿的指定幻灯片保存为带有指定格式的文件，并保留页码。 |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 将演示文稿的指定幻灯片保存到指定格式的流中，并保留页码。 |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 将演示文稿的指定幻灯片保存到指定格式的流中，并保留页码。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 在所有幻灯片的所有可接受形状的所有段落中，合并具有相同格式的运行。 |
| [dispose()](#dispose--) | 释放此 Presentation 对象使用的所有资源。 |
| [getPresentation()](#getPresentation--) | 返回文本所属的父演示文稿。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 使用指定颜色高亮显示所有匹配的示例文本。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 使用指定颜色高亮显示所有匹配的示例文本。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 使用指定颜色高亮显示正则表达式的所有匹配项。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 将指定文本的所有出现替换为另一个指定文本。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 将正则表达式的所有匹配替换为指定字符串。 |
| [refreshChartsData()](#refreshChartsData--) | 从源工作簿重新加载演示文稿中所有图表的数据。 |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | 从源工作簿重新加载演示文稿中所有图表的数据。 |
### Presentation() {#Presentation--}
```
public Presentation()
```

此构造函数从头创建新的演示文稿。创建的演示文稿包含一个空白幻灯片。

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

此构造函数从头创建新的演示文稿。创建的演示文稿包含一个空白幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 附加的加载选项。 |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

此构造函数是读取现有 Presentation 的主要机制。

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 输入流。 |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

此构造函数是读取现有 Presentation 的主要机制。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 输入流。 |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 附加的加载选项。 |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

此构造函数获取用于读取 Presentation 内容的源文件路径。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 输入文件。 |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

此构造函数获取用于读取 Presentation 内容的源文件路径。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 输入文件。 |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 附加的加载选项。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

返回或设置用于替代日期时间字段内容的日期和时间。默认是此 Presentation 对象创建的时间。Read/write java.util.Date。

**返回值:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

返回或设置用于替代日期时间字段内容的日期和时间。默认是此 Presentation 对象创建的时间。Read/write java.util.Date。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回值:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

返回实际的 HeaderFooter 管理器。只读 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)。

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // 属性 IsFooterVisible 用于指示幻灯片页脚占位符不存在。
>      {
>          headerFooterManager.setFooterVisibility(true); // 方法 SetFooterVisibility 用于使幻灯片页脚占位符可见。
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // 属性 IsSlideNumberVisible 用于指示幻灯片页码占位符不存在。
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // 方法 SetSlideNumberVisibility 用于使幻灯片页码占位符可见。
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // 属性 IsDateTimeVisible 用于指示幻灯片日期时间占位符不存在。
>      {
>          headerFooterManager.setDateTimeVisibility(true); // 方法 SetFooterVisibility 用于使幻灯片日期时间占位符可见。
>      }
>      headerFooterManager.setFooterText("Footer text"); // 方法 SetFooterText 用于设置幻灯片页脚占位符的文本。
>      headerFooterManager.setDateTimeText("Date and time text"); // 方法 SetDateTimeText 用于设置幻灯片日期时间占位符的文本。
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // 方法 SetFooterAndChildFootersVisibility 用于使母版幻灯片及所有子页脚占位符可见。
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // 方法 SetSlideNumberAndChildSlideNumbersVisibility 用于使母版幻灯片及所有子页码占位符可见。
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // 方法 SetDateTimeAndChildDateTimesVisibility 用于使母版幻灯片及所有子日期时间占位符可见。
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // 方法 SetFooterAndChildFootersText 用于设置母版幻灯片及所有子页脚占位符的文本。
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // 方法 SetDateTimeAndChildDateTimesText 用于设置母版幻灯片及所有子日期时间占位符的文本。
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

获取此演示文稿的权限管理器。只读 [IProtectionManager](../../com.aspose.slides/iprotectionmanager)。

**返回值:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

返回演示文稿中定义的所有幻灯片的列表。只读 [ISlideCollection](../../com.aspose.slides/islidecollection)。

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // 实例化表示演示文稿文件的 Presentation 类
>  Presentation pres = new Presentation();
>  try
>  {
>      // 将第一张 ISlide 的背景颜色设置为蓝色
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // 实例化表示演示文稿文件的 Presentation 类
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // 使用图片设置背景
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // 设置图片
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // 将图片添加到演示文稿的图片集合中
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // 将演示文稿写入磁盘
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // 实例化 Presentation 类以加载源演示文稿文件
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // 在第 1 张幻灯片上应用圆形过渡效果
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // 在第 2 张幻灯片上应用梳状过渡效果
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // 将演示文稿写入磁盘
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // 实例化表示演示文稿文件的 Presentation 类
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // 在第 1 张幻灯片上应用圆形过渡效果
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // 设置 3 秒的过渡时间
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // 在第 2 张幻灯片上应用梳状过渡效果
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // 设置 5 秒的过渡时间
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // 在第 3 张幻灯片上应用缩放过渡效果
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // 设置 7 秒的过渡时间
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // 将演示文稿写入磁盘
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

返回演示文稿中定义的所有幻灯片章节的列表。只读 [ISectionCollection](../../com.aspose.slides/isectioncollection)。

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 将在 newSlide2 结束，之后将开始 section2
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

返回幻灯片尺寸对象。只读 [ISlideSize](../../com.aspose.slides/islidesize)。

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // 实例化表示演示文稿文件的 Presentation 对象
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // 将生成的演示文稿的幻灯片尺寸设置为与源相同
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // 方法 SetSize 用于在缩放内容以确保适配时设置幻灯片尺寸
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // 方法 SetSize 用于在最大化内容尺寸时设置幻灯片尺寸
>          // 将演示文稿保存到磁盘
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 纸张尺寸
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

返回备注幻灯片尺寸对象。只读 [INotesSize](../../com.aspose.slides/inotessize)。

**返回值:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

返回演示文稿中定义的所有布局幻灯片的列表。只读 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

--------------------

您可以通过使用 IMasterSlide.LayoutSlides 属性访问用于添加/插入/删除/克隆布局幻灯片的替代 API。

**返回值:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

返回演示文稿中定义的所有母版幻灯片的列表。只读 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)。

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // 实例化表示演示文稿文件的 Presentation 类
>  Presentation pres = new Presentation();
>  try
>  {
>      // 将母版 ISlide 的背景颜色设置为森林绿
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // 将演示文稿写入磁盘
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // 实例化表示演示文稿文件的 Presentation 类
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // 尝试按布局幻灯片类型搜索
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // 演示文稿不包含某些类型布局的情况。
>          // 演示文稿文件仅包含空白和自定义布局类型。
>          // 但自定义类型的布局幻灯片有不同的幻灯片名称，
>          // 例如 "Title", "Title and Content", 等，并且可以使用这些
>          // 名称来选择布局幻灯片。
>          // 还可以使用占位符形状类型集合。例如，
>          // 标题幻灯片应仅包含 Title 占位符类型，等。
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // 使用已添加的布局幻灯片添加空白幻灯片
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // 保存演示文稿
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回值:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

返回备注母版管理器。只读 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)。

**返回值:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

返回讲义母版管理器。只读 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)。

**返回值:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

返回字体管理器。只读 [IFontsManager](../../com.aspose.slides/ifontsmanager)。

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // 加载演示文稿
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // 加载要替换的源字体
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // 保存演示文稿
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

返回形状的默认文本样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回值:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

返回评论作者的集合。只读 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)。

**返回值:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

返回包含标准和自定义文档属性的 DocumentProperties 对象。只读 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)。

**返回值:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

返回演示文稿中所有图像的集合。只读 [IImageCollection](../../com.aspose.slides/iimagecollection)。

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // 创建一个将要添加图像的新演示文稿。
>  Presentation pres = new Presentation();
>  try
>  {
>      // 假设我们有要嵌入演示文稿的大图像文件
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // 让我们将图像添加到演示文稿 - 我们选择 KeepLocked 行为，因为我们
>          // 不打算访问 "largeImage.png" 文件。
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // 保存演示文稿。即使输出大型演示文稿，内存消耗
>          // 在 pres 对象生命周期内保持低水平
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // 将图像添加到演示文稿
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // 基于先前添加的图像在第 1 张幻灯片上创建图片框
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```
返回演示文稿中所有嵌入的音频文件的集合。只读 [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```


返回演示文稿中所有嵌入的视频文件的集合。只读 [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**返回：**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


返回演示文稿的幻灯片放映设置。

**返回：**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


返回用于签署演示文稿的签名集合。只读 [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


返回演示文稿的自定义数据。只读 [ICustomData](../../com.aspose.slides/icustomdata).

**返回：**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


返回演示文稿中所有自定义数据部件。只读 ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // 遍历所有自定义 XML 部分
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


获取或设置带有演示文稿宏的 VBA 项目。读写 [IVbaProject](../../com.aspose.slides/ivbaproject).

**返回：**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


获取或设置带有演示文稿宏的 VBA 项目。读写 [IVbaProject](../../com.aspose.slides/ivbaproject).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


提供对所有演示文稿幻灯片（不包括母版、布局、备注幻灯片）中包含的所有超链接的便捷访问。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**返回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


获取整个演示文稿的视图属性。只读 [IViewProperties](../../com.aspose.slides/iviewproperties).

**返回：**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


表示演示文稿中的第一张幻灯片编号

**返回：**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


表示演示文稿中的第一张幻灯片编号

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```


返回应用于演示文稿的敏感度标签集合。只读 [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // 打印已应用的标签
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // 添加新标签
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // 从策略获取敏感度标签 ID
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // 从策略获取 Azure AD 站点标识符
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | long | 幻灯片的 Id。 |

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide 对象。
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


返回演示文稿加载自何种格式的信息。只读 [SourceFormat](../../com.aspose.slides/sourceformat).

**返回：**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


返回母版主题。只读 [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> 以下示例展示了如何通过修改 PowerPoint 演示文稿中元素的部分来更改主题效果。
>  
>  //实例化表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


将演示文稿的所有幻灯片保存到具有指定格式的文件中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


将演示文稿的所有幻灯片以指定格式保存到流中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


将演示文稿的所有幻灯片保存到具有指定格式并附加选项的文件中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


将演示文稿的所有幻灯片以指定格式并附加选项保存到流中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


将演示文稿的所有幻灯片保存为一组表示 XAML 标记的文件。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML 格式选项。 |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```


返回演示文稿所有幻灯片的 Image 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 选项。 |

**返回：**
com.aspose.slides.IImage[] - Image 对象。
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


返回演示文稿指定幻灯片的缩略图 Image 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始值为 1。 |

**返回：**
com.aspose.slides.IImage[] - Image 对象。
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


返回演示文稿所有幻灯片的缩略图 Image 对象，使用自定义缩放。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 选项。 |
| scaleX | float | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 y 轴方向上缩放此缩略图的值。 |

**返回：**
com.aspose.slides.IImage[] - Image 对象。
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


返回演示文稿指定幻灯片的缩略图 Image 对象，使用自定义缩放。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始值为 1。 |
| scaleX | float | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 y 轴方向上缩放此缩略图的值。 |

**返回：**
com.aspose.slides.IImage[] - Image 对象。
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


返回演示文稿所有幻灯片的缩略图 Image 对象，使用指定的大小。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 选项。 |
| imageSize | java.awt.Dimension | 要创建的图像大小。 |

**返回：**
com.aspose.slides.IImage[] - Image 对象。
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


返回演示文稿指定幻灯片的缩略图 Image 对象，使用指定的大小。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff 选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始值为 1。 |
| imageSize | java.awt.Dimension | 要创建的图像大小。 |

**返回：**
com.aspose.slides.IImage[] - Image 对象。
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


将演示文稿的指定幻灯片保存到具有指定格式且保留页码的文件中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 创建的文件路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始值为 1。 |
| format | int | 导出数据的格式。 |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


将演示文稿的指定幻灯片保存到具有指定格式且保留页码的文件中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 创建的文件路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始值为 1。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


将演示文稿的指定幻灯片以指定格式且保留页码保存到流中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始值为 1。 |
| format | int | 导出数据的格式。 |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


将演示文稿的指定幻灯片以指定格式且保留页码保存到流中。

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始值为 1。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


在所有幻灯片的所有可接受形状的所有段落中，合并具有相同格式的文本段。
### dispose() {#dispose--}
```
public final void dispose()
```


释放此 Presentation 对象使用的所有资源。
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


返回文本所在的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation).

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


使用指定颜色突出显示示例文本的所有匹配项。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 突出显示所有单独的 'the' 出现
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


使用指定颜色突出显示示例文本的所有匹配项。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 突出显示所有单独的 'the' 出现
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


使用指定颜色突出显示正则表达式的所有匹配项。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 突出显示所有长度为10个字符或更长的单词
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| regex | java.util.regex.Pattern | 用于获取要高亮显示的字符串的正则表达式 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | 用于高亮文本的颜色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

将指定文本的所有出现替换为另一个指定文本。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 将所有单独的 'the' 出现替换为 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | 要被替换的字符串。 |
| newText | java.lang.String | 用于替换 oldText 所有出现的字符串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

将正则表达式的所有匹配项替换为指定字符串。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 将所有长度为10个字符或更长的单词替换为 '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要替换字符串的正则表达式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用于替换所有被替换字符串出现的字符串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```

从源工作簿重新加载演示文稿中所有图表的数据。

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public final void refreshChartsData(boolean skipFailedCharts)
```

从源工作簿重新加载演示文稿中所有图表的数据。

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| skipFailedCharts | boolean | 确定当图表更新失败时刷新过程是否继续。如果为 true，则跳过导致异常的图表；否则异常会被传播。 |