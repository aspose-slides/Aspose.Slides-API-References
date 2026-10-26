---
title: IPresentation
second_title: Aspose.Slides for Java API 参考
description: 演示文稿
type: docs
url: /zh/com.aspose.slides/ipresentation/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

演示文稿
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 返回或设置将替代日期时间字段内容的日期和时间。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 返回或设置将替代日期时间字段内容的日期和时间。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回演示文稿的 HeaderFooter 管理器。 |
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
| [getAudios()](#getAudios--) | 返回演示文稿中所有嵌入的音频文件的集合。 |
| [getVideos()](#getVideos--) | 返回演示文稿中所有嵌入的视频文件的集合。 |
| [getCustomData()](#getCustomData--) | 返回演示文稿的自定义数据。 |
| [getVbaProject()](#getVbaProject--) | 获取包含演示文稿宏的 VBA 项目。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 获取包含演示文稿宏的 VBA 项目。 |
| [getSourceFormat()](#getSourceFormat--) | 返回有关演示文稿是从哪种格式加载的信息。 |
| [getMasterTheme()](#getMasterTheme--) | 返回演示文稿的母版主题。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供对所有演示文稿幻灯片中包含的超链接的便捷访问（不包括母版、布局、备注幻灯片）。 |
| [getViewProperties()](#getViewProperties--) | 获取整个演示文稿的视图属性。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 表示演示文稿中的第一张幻灯片编号。 |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 表示演示文稿中的第一张幻灯片编号。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 返回演示文稿中的所有自定义数据部件。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | 返回用于签署演示文稿的签名集合。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 返回应用于演示文稿的敏感度标签集合。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 将演示文稿的所有幻灯片保存为具有指定格式的文件。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 将演示文稿的所有幻灯片保存到指定格式的流中。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 将演示文稿的所有幻灯片保存为具有指定格式并附加选项的文件。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 将演示文稿的所有幻灯片保存到具有指定格式并附加选项的流中。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | 将演示文稿的指定幻灯片保存为具有指定格式的文件。 |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | 将演示文稿的指定幻灯片保存为具有指定格式的文件。 |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | 将演示文稿的指定幻灯片保存到指定格式的流中。 |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | 将演示文稿的指定幻灯片保存到指定格式的流中。 |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | 将演示文稿的所有幻灯片保存为一组表示 XAML 标记的文件。 |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | 返回演示文稿所有幻灯片的缩略图图像对象。 |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | 返回演示文稿指定幻灯片的缩略图 IImage 对象。 |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | 返回使用自定义缩放的演示文稿所有幻灯片的缩略图图像对象。 |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | 返回使用自定义缩放的演示文稿指定幻灯片的缩略图图像对象。 |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 返回使用指定尺寸的演示文稿所有幻灯片的缩略图图像对象。 |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | 返回使用指定尺寸的演示文稿指定幻灯片的缩略图图像对象。 |
| [getSlideById(long id)](#getSlideById-long-) | 根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合并所有幻灯片中所有可接受形状的所有段落中具有相同格式的运行。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 使用指定颜色高亮显示样本文本的所有匹配项。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 使用指定颜色高亮显示样本文本的所有匹配项。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 使用指定颜色高亮显示正则表达式的所有匹配项。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 将所有出现的指定文本替换为另一个指定文本。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 将正则表达式的所有匹配替换为指定的字符串。 |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

返回或设置将替代日期时间字段内容的日期和时间。默认是此 Presentation 对象创建的时间。可读写 java.util.Date。

**返回：**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

返回或设置将替代日期时间字段内容的日期和时间。默认是此 Presentation 对象创建的时间。可读写 java.util.Date。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

返回演示文稿的 HeaderFooter 管理器。只读 [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)。

**返回：**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

获取此演示文稿的权限管理器。只读 [IProtectionManager](../../com.aspose.slides/iprotectionmanager)。

**返回：**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

返回演示文稿中定义的所有幻灯片的列表。只读 [ISlideCollection](../../com.aspose.slides/islidecollection)。

**返回：**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

返回演示文稿中定义的所有幻灯片章节的列表。只读 [ISectionCollection](../../com.aspose.slides/isectioncollection)。

**返回：**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

返回幻灯片大小对象。只读 [ISlideSize](../../com.aspose.slides/islidesize)。

**返回：**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

返回备注幻灯片大小对象。只读 [INotesSize](../../com.aspose.slides/inotessize)。

**返回：**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

返回演示文稿中定义的所有布局幻灯片的列表。只读 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

--------------------

您可以通过使用 IMasterSlide.LayoutSlides 属性访问用于添加/插入/删除/克隆布局幻灯片的替代 API。

**返回：**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

返回演示文稿中定义的所有母版幻灯片的列表。只读 [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)。

**返回：**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

返回备注母版管理器。只读 [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)。

**返回：**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

返回讲义母版管理器。只读 [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)。

**返回：**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

返回字体管理器。只读 [IFontsManager](../../com.aspose.slides/ifontsmanager)。

**返回：**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

返回形状的默认文本样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回：**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

返回评论作者的集合。只读 [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)。

**返回：**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

返回包含标准和自定义文档属性的 DocumentProperties 对象。只读 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)。

**返回：**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

返回演示文稿中所有图像的集合。只读 [IImageCollection](../../com.aspose.slides/iimagecollection)。

**返回：**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

返回演示文稿中所有嵌入的音频文件的集合。只读 [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

**返回：**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

返回演示文稿中所有嵌入的视频文件的集合。只读 [IVideoCollection](../../com.aspose.slides/ivideocollection)。

**返回：**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

返回演示文稿的自定义数据。只读 [ICustomData](../../com.aspose.slides/icustomdata)。

**返回：**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

获取包含演示文稿宏的 VBA 项目。可读写 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**返回：**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

获取包含演示文稿宏的 VBA 项目。可读写 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

返回有关演示文稿是从哪种格式加载的信息。只读 [SourceFormat](../../com.aspose.slides/sourceformat)。

**返回：**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

返回演示文稿的母版主题。只读 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**返回：**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

提供对所有演示文稿幻灯片中包含的超链接的便捷访问（不包括母版、布局、备注幻灯片）。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

获取整个演示文稿的视图属性。只读 [IViewProperties](../../com.aspose.slides/iviewproperties)。

**返回：**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

表示演示文稿中的第一张幻灯片编号。可读写 int。

**返回：**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

表示演示文稿中的第一张幻灯片编号。可读写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

返回演示文稿中的所有自定义数据部件。只读 ICustomXmlPart[]。

**返回：**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

返回用于签署演示文稿的签名集合。只读 [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)。

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

返回应用于演示文稿的敏感度标签集合。只读 [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Print the applied labels
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Add the new label
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Get the sensitivity label Id from the policy
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Get the Azure AD site identifier from the policy
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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

将演示文稿的所有幻灯片保存为具有指定格式的文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 要创建的文件的路径。 |
| format | int | 导出数据的格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

将演示文稿的所有幻灯片保存到指定格式的流中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

将演示文稿的所有幻灯片保存为具有指定格式并附加选项的文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | java.lang.String | 要创建的文件的路径。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

将演示文稿的指定幻灯片保存到文件中，使用指定的格式。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | 创建的文件路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始索引为 1。 |
| format | int | 导出数据的格式。 |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

将演示文稿的指定幻灯片保存到文件中，使用指定的格式。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | 创建的文件路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始索引为 1。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

将演示文稿的指定幻灯片保存到流中，使用指定的格式。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始索引为 1。 |
| format | int | 导出数据的格式。 |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

将演示文稿的指定幻灯片保存到流中，使用指定的格式。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始索引为 1。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 附加的格式选项。 |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML 格式选项。 |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

返回演示文稿所有幻灯片的缩略图 Image 对象。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |

**返回：**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

返回演示文稿指定幻灯片的缩略图 IImage 对象。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始索引为 1。 |

**返回：**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

返回演示文稿所有幻灯片的缩略图 Image 对象，使用自定义缩放。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| scaleX | float | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 y 轴方向上缩放此缩略图的值。 |

**返回：**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

返回演示文稿指定幻灯片的缩略图 Image 对象，使用自定义缩放。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始索引为 1。 |
| scaleX | float | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 y 轴方向上缩放此缩略图的值。 |

**返回：**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

返回演示文稿所有幻灯片的指定大小的缩略图 Image 对象。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| imageSize | java.awt.Dimension | 要创建的图像大小。 |

**返回：**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

返回演示文稿指定幻灯片的指定大小的缩略图 Image 对象。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始索引为 1。 |
| imageSize | java.awt.Dimension | 要创建的图像大小。 |

**返回：**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | 幻灯片的 Id。 |

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

在所有幻灯片的所有可接受形状中的所有段落里，将具有相同格式的文本段合并。

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

使用指定颜色突出显示所有匹配的示例文本。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 高亮所有单独出现的 'the' occurrences
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

使用指定颜色突出显示所有匹配的示例文本。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // 高亮所有单独出现的 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

使用指定颜色突出显示所有匹配的正则表达式。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // highlighting all separate 'the' occurrences
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要突出显示字符串的正则表达式 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

将指定文本的所有出现替换为另一个指定文本。

--------------------

> ```
> 以下示例代码展示了如何将一个指定的字符串替换为另一个指定的字符串。
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 将所有单独出现的 'the' 替换为 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | 要被替换的字符串。 |
| newText | java.lang.String | 用于替换 oldText 所有出现的字符串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

使用指定字符串替换正则表达式的所有匹配项。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 将所有单独出现的 'the' 替换为 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要替换字符串的正则表达式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用于替换所有待替换字符串出现的字符串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |