---
title: IPresentation
second_title: Aspose.Slides for Android via Java API 参考
description: 演示文稿
type: docs
url: /zh/com.aspose.slides/ipresentation/
---
**所有实现的接口：**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

演示文稿
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | 返回或设置将替代 datetime 字段内容的日期和时间。 |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | 返回或设置将替代 datetime 字段内容的日期和时间。 |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回演示文稿的 HeaderFooter 管理器。 |
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
| [getAudios()](#getAudios--) | 返回演示文稿中所有嵌入式音频文件的集合。 |
| [getVideos()](#getVideos--) | 返回演示文稿中所有嵌入式视频文件的集合。 |
| [getCustomData()](#getCustomData--) | 返回演示文稿的自定义数据。 |
| [getVbaProject()](#getVbaProject--) | 获取包含演示文稿宏的 VBA 项目。 |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | 获取包含演示文稿宏的 VBA 项目。 |
| [getSourceFormat()](#getSourceFormat--) | 返回关于演示文稿是从哪种格式加载的信息。 |
| [getMasterTheme()](#getMasterTheme--) | 返回演示文稿的母版主题。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供对所有演示文稿幻灯片（不包括母版、布局、备注幻灯片）中包含的所有超链接的便捷访问。 |
| [getViewProperties()](#getViewProperties--) | 获取整个演示文稿的视图属性。 |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | 表示演示文稿中的第一页编号。 |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | 表示演示文稿中的第一页编号。 |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | 返回演示文稿中的所有自定义数据部件。 |
| [getDigitalSignatures()](#getDigitalSignatures--) | 返回用于签署演示文稿的签名集合。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 返回应用于演示文稿文档的敏感度标签集合。 |
| [save(String fname, int format)](#save-java.lang.String-int-) | 将演示文稿的所有幻灯片保存为指定格式的文件。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 将演示文稿的所有幻灯片以指定格式保存到流中。 |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用额外选项。 |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | 将演示文稿的所有幻灯片以指定格式保存到流中，并使用额外选项。 |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail Image objects for all slides of a presentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Returns a Thumbnail IImage objects for specified slides of a presentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail Image objects for all slides of a presentation with custom scaling. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail Image objects for all slides of a presentation with specified size. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [getSlideById(long id)](#getSlideById-long-) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Highlights all matches of the sample text with the specified color. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Highlights all matches of the sample text with the specified color. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Highlights all matches of the regular expression with the specified color. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Replaces all occurrences of the specified text with another specified text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Replaces all matches of the regular expression with the specified string. |
### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

返回或设置将替代 datetime 字段内容的日期和时间。默认情况下为此 Presentation 对象创建的时间。读写 java.util.Date。

**返回：**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

返回或设置将替代 datetime 字段内容的日期和时间。默认情况下为此 Presentation 对象创建的时间。读写 java.util.Date。

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

返回幻灯片尺寸对象。只读 [ISlideSize](../../com.aspose.slides/islidesize)。

**返回：**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

返回备注幻灯片尺寸对象。只读 [INotesSize](../../com.aspose.slides/inotessize)。

**返回：**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

返回演示文稿中定义的所有布局幻灯片的列表。只读 [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)。

您可以通过使用 IMasterSlide.LayoutSlides 属性来访问用于添加/插入/删除/克隆布局幻灯片的替代 API。

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

返回演示文稿中所有嵌入式音频文件的集合。只读 [IAudioCollection](../../com.aspose.slides/iaudiocollection)。

**返回：**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

返回演示文稿中所有嵌入式视频文件的集合。只读 [IVideoCollection](../../com.aspose.slides/ivideocollection)。

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

获取包含演示文稿宏的 VBA 项目。读写 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**返回：**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

获取包含演示文稿宏的 VBA 项目。读写 [IVbaProject](../../com.aspose.slides/ivbaproject)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

返回关于演示文稿是从哪种格式加载的信息。只读 [SourceFormat](../../com.aspose.slides/sourceformat)。

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

提供对所有演示文稿幻灯片（不包括母版、布局、备注幻灯片）中包含的所有超链接的便捷访问。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

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

表示演示文稿中的第一页编号。读写 int。

**返回：**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

表示演示文稿中的第一页编号。读写 int。

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

**Returns:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```


Returns the collection of sensitivity labels applied to the presentation document. Read-only [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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

**Returns:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Saves all slides of a presentation to a file with the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Saves all slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
将演示文稿的所有幻灯片保存为指定格式的文件，并使用额外的选项。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | 创建文件的路径。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 额外的格式选项。 |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

将演示文稿的所有幻灯片保存到流中，以指定的格式，并使用额外的选项。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 额外的格式选项。 |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```
将演示文稿的指定幻灯片保存为带有指定格式的文件。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```
将演示文稿的指定幻灯片保存为带有指定格式的文件。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Saves specified slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Saves specified slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Saves all slides of a presentation to a set of files representing XAML markup.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | The XAML format options. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```


Returns a Thumbnail Image objects for all slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Returns a Thumbnail IImage objects for specified slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Returns a Thumbnail Image objects for all slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
com.aspose.slides.IImage[] - Bitmap objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Returns a Thumbnail Image objects for all slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```


Returns a Thumbnail Image objects for specified slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

返回一个 Slide、MasterSlide 或 LayoutSlide，按 Id。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | long | 幻灯片的 Id。 |

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide 对象。
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```
Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Highlights all matches of the sample text with the specified color.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.lang.Integer | 用于突出显示文本的颜色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

使用指定颜色突出显示正则表达式的所有匹配项。

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要突出显示字符串的正则表达式 java.util.regex.Pattern。 |
| highlightColor | java.lang.Integer | 用于突出显示文本的颜色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

将指定文本的所有出现替换为另一个指定文本。

--------------------

> ```
> 以下示例代码展示如何将一个指定字符串替换为另一个指定字符串。
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 将所有单独的 'the' 出现替换为 '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>      } finally {
>      if (presentation != null) presentation.dispose();
>      }
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | 要被替换的字符串。 |
| newText | java.lang.String | 用于替换 oldText 所有出现的字符串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
Replaces all matches of the regular expression with the specified string.
--------------------
> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Replace all separate 'the' occurrences with '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  ```
**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取待替换字符串的正则表达式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用于替换所有待替换字符串的字符串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |