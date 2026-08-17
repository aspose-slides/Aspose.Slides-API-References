---
title: Presentation
second_title: Aspose.Slides for Java API 参考
description: 表示 Microsoft PowerPoint 演示文稿。
type: docs
url: /zh/com.aspose.slides/presentation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
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
>      // 添加类型为直线的自动形状
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // 保存演示文稿文件。
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // 加载 Presentation 中的任何支持的文件，例如 ppt、pptx、odp 等。
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
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | 此构造函数是读取现有演示文稿的主要机制。 |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | 此构造函数是读取现有演示文稿的主要机制。 |
| [Presentation(String file)](#Presentation-java.lang.String-) | 此构造函数获取演示文稿内容读取的源文件路径。 |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | 此构造函数获取演示文稿内容读取的源文件路径。 |

## 方法

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 返回或设置将替代日期时间字段内容的日期和时间。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 返回或设置将替代日期时间字段内容的日期和时间。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回实际的 HeaderFooter 管理器。 |
| [getProtectionManager()](#getProtectionManager--) | 获取此演示文稿的权限管理器。 |
| [getSlides()](#getSlides--) | 返回演示文稿中定义的所有幻灯片的列表。 |
| [getSections()](#getSections--) | 返回演示文稿中定义的所有幻灯片章节的列表。 |
| [getSlideSize()](#getSlideSize--) | 返回幻灯片大小对象。 |
| [getNotesSize()](#getNotesSize--) | 返回备注幻灯片大小对象。 |
| [getLayoutSlides()](#getLayoutSlides--) | 返回演示文稿中定义的所有布局幻灯片的列表。 |
| [getMasters()](#getMasters--) | 返回演示文稿中定义的所有母版幻灯片的列表。 |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | 返回备注母版管理器。 |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | 返回讲义母版管理器。 |
| [getFontsManager()](#getFontsManager--) | 返回字体管理器。 |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | 返回形状的默认文本样式。 |
| [getCommentAuthors()](#getCommentAuthors--) | 返回评论作者的集合。 |
| [getDocumentProperties()](#getDocumentProperties--) | 返回包含标准和自定义文档属性的 DocumentProperties 对象。 |
| [getImages()](#getImages--) | 返回演示文稿中所有图像的集合。 |
| [getAudios()](#getAudios--) | 返回演示文稿中所有嵌入式音频文件的集合。 |
| [getVideos()](#getVideos--) | 返回演示文稿中所有嵌入式视频文件的集合。 |
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
| [getSensitivityLabels()](#getSensitivityLabels--) | 返回应用于演示文稿的敏感度标签集合。 |
| [getSlideById(long id)](#getSlideById-long-) | 根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |
| [getSourceFormat()](#getSourceFormat--) | 返回有关演示文稿加载自哪种格式的信息。 |
| [getMasterTheme()](#getMasterTheme--) | 返回母版主题。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 将演示文稿的所有幻灯片保存为指定格式的文件。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 将演示文稿的所有幻灯片保存到指定格式的流中。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 将演示文稿的所有幻灯片保存为指定格式的文件并使用附加选项。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 将演示文稿的所有幻灯片保存到指定格式的流中并使用附加选项。 |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 将演示文稿的所有幻灯片保存为表示 XAML 标记的一组文件。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 返回演示文稿所有幻灯片的 Image 对象。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 返回演示文稿指定幻灯片的缩略图 Image 对象。 |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 返回演示文稿所有幻灯片的缩略图 Image 对象，使用自定义缩放。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 返回演示文稿指定幻灯片的缩略图 Image 对象，使用自定义缩放。 |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 返回演示文稿所有幻灯片的缩略图 Image 对象，使用指定尺寸。 |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | 返回演示文稿指定幻灯片的缩略图 Image 对象，使用指定尺寸。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 将演示文稿的指定幻灯片保存为具有指定格式且保留页码的文件。 |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 将演示文稿的指定幻灯片保存为具有指定格式且保留页码的文件。 |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 将演示文稿的指定幻灯片保存为具有指定格式且保留页码的文件。 |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 将演示文稿的指定幻灯片保存为具有指定格式且保留页码的文件。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 在所有幻灯片的所有可接受形状的所有段落中合并具有相同格式的文本段。 |
| [dispose()](#dispose--) | 释放此 Presentation 对象使用的所有资源。 |
| [getPresentation()](#getPresentation--) | 返回文本所在的父级演示文稿。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 使用指定颜色突出显示所有匹配的示例文本。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 使用指定颜色突出显示所有匹配的示例文本。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 将指定文本的所有出现替换为另一个指定文本。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 将正则表达式的所有匹配项替换为指定字符串。 |

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
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 其他加载选项。 |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

此构造函数是读取现有演示文稿的主要机制。

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | 输入流。 |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

此构造函数是读取现有演示文稿的主要机制。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | 输入流。 |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 其他加载选项。 |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

此构造函数获取演示文稿内容读取的源文件路径。

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | 输入文件。 |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

此构造函数获取演示文稿内容读取的源文件路径。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | 输入文件。 |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | 其他加载选项。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

返回或设置将替代日期时间字段内容的日期和时间。默认情况下为此 Presentation 对象创建的时间。可读写 java.util.Date。

**返回值:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

返回或设置将替代日期时间字段内容的日期和时间。默认情况下为此 Presentation 对象创建的时间。可读写 java.util.Date。

**参数:**
| Parameter | Type | Description |
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
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible is used for indicating that a slide footer placeholder is not present.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility is used for making a slide footer placeholder visible.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible is used for indicating that a slide page number placeholder is not present.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility is used for making a slide page number placeholder visible.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible is used for indicating that a slide date-time placeholder is not present.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility is used for making a slide date-time placeholder visible.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText is used for setting text to slide footer placeholder.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText is used for setting text to slide date-time placeholder.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility is used for making a master slide and all child footer placeholders visible.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility is used for making a master slide and all child page number placeholders visible.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility is used for making a master slide and all child date-time placeholders visible.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText is used for setting text to master slide and all child footer placeholders.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText is used for setting text to master slide and all child date-time placeholders.
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
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the first ISlide to Blue
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
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Set the background with Image
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Set the picture
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Add image to presentation's images collection
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Write the presentation to disk
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Write the presentation to disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instantiate Presentation class that represents a presentation file
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Set the transition time of 3 seconds
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Set the transition time of 5 seconds
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Apply zoom type transition on slide 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Set the transition time of 7 seconds
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Write the presentation to disk
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
>      // section1 将在 newSlide2 结束，随后 section2 将开始
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

返回幻灯片大小对象。只读 [ISlideSize](../../com.aspose.slides/islidesize)。

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
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Set the slide size of generated presentations to that of source
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize is used for set slide size with scale content to ensure fit
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize is used for set slide size with maximize size of content
>          // Save Presentation to disk
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 paper size
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

返回备注幻灯片大小对象。只读 [INotesSize](../../com.aspose.slides/inotessize)。

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
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the Master ISlide to Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Write the presentation to disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Try to search by layout slide type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // The situation when a presentation doesn't contain some type of layouts.
>          // presentation File only contains Blank and Custom layout types.
>          // But layout slides with Custom types has different slide names,
>          // like "Title", "Title and Content", etc. And it is possible to use these
>          // names for layout slide selection.
>          // Also it is possible to use the set of placeholder shape types. For example,
>          // Title slide should have only Title pleceholder type, etc.
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
>      // Adding empty slide with added layout slide
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
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
>  // Load presentation
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Load source font to be replaced
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
>      // Save the presentation
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
>  // creates a new presentation to which the image will be added.
>  Presentation pres = new Presentation();
>  try
>  {
>      // supposed we have the large image file we want to include into the presentation
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Let's add the image to the presentation - we choose KeepLocked behavior because we do
>          // NOT intend to access the "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
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
>      // Adds image to presentation
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Creates picture frame on slide 1 based on previously added image
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

返回演示文稿中所有嵌入式音频文件的集合。只读 [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

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

**返回值:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
返回演示文稿中所有嵌入视频文件的集合。只读 [IVideoCollection](../../com.aspose.slides/ivideocollection).

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

返回演示文稿的自定义数据。只读 [ICustomData](../../com.aspose.slides/icustomdata)。

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

获取或设置带有演示文稿宏的 VBA 项目。读/写 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**返回：**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

获取或设置带有演示文稿宏的 VBA 项目。读/写 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

提供对所有演示文稿幻灯片（不包括母版、布局、备注幻灯片）中包含的超链接的简便访问。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

获取演示文稿范围的视图属性。只读 [IViewProperties](../../com.aspose.slides/iviewproperties)。

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

返回应用于演示文稿文档的敏感度标签集合。只读 [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // 从策略获取敏感标签 ID
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

返回有关演示文稿从哪种格式加载的信息。只读 [SourceFormat](../../com.aspose.slides/sourceformat)。

**返回：**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

返回母版主题。只读 [IMasterTheme](../../com.aspose.slides/imastertheme)。

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // 实例化表示演示文稿文件的 Presentation 对象
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

将演示文稿的所有幻灯片保存到指定格式的文件中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

将演示文稿的所有幻灯片保存到指定格式的流中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

将演示文稿的所有幻灯片保存到指定格式的文件中，并使用附加选项。

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

将演示文稿的所有幻灯片保存到指定格式的流中，并使用附加选项。

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
| slides | int[] | 从 1 开始的幻灯片位置数组。 |

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
| slides | int[] | 从 1 开始的幻灯片位置数组。 |
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
| imageSize | java.awt.Dimension | 要创建的图像的尺寸。 |

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
| slides | int[] | 从 1 开始的幻灯片位置数组。 |
| imageSize | java.awt.Dimension | 要创建的图像的尺寸。 |

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
| slides | int[] | 从 1 开始的幻灯片位置数组。 |
| format | int | 导出数据的格式。 |
### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

将演示文稿的指定幻灯片保存到具有指定格式且保留页码的文件中，并使用附加选项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 创建的文件路径。 |
| slides | int[] | 从 1 开始的幻灯片位置数组。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |
### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

将演示文稿的指定幻灯片保存到具有指定格式且保留页码的流中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| slides | int[] | 从 1 开始的幻灯片位置数组。 |
| format | int | 导出数据的格式。 |
### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

将演示文稿的指定幻灯片保存到具有指定格式且保留页码的流中，并使用附加选项。

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
| slides | int[] | 从 1 开始的幻灯片位置数组。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

在所有幻灯片的所有可接受形状中的所有段落中，合并具有相同格式的运行。
### dispose() {#dispose--}
```
public final void dispose()
```

释放此 Presentation 对象使用的所有资源。
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回文本的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

用指定颜色高亮显示示例文本的所有匹配项。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 对所有单独的 'the' 出现进行高亮
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要高亮的文本。 |
| highlightColor | java.awt.Color | 用于高亮文本的颜色。 |
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

用指定颜色高亮显示示例文本的所有匹配项。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 对所有单独的 'the' 出现进行高亮
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要高亮的文本。 |
| highlightColor | java.awt.Color | 用于高亮文本的颜色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

用指定颜色高亮显示正则表达式的所有匹配项。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 高亮所有长度为10个字符或更长的单词
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要高亮字符串的正则表达式 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | 用于高亮文本的颜色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldText | java.lang.String | 要被替换的字符串。 |
| newText | java.lang.String | 用于替换所有 oldText 出现的字符串。 |
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
>      // Replace all words with 10 symbols or longer with '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要替换的字符串的正则表达式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用于替换所有待替换字符串出现的字符串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |