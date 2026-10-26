---
title: LoadOptions
second_title: Aspose.Slides for Java API 参考
description: 在加载演示文稿时，允许指定额外的选项，例如格式或默认字体。
type: docs
url: /zh/com.aspose.slides/loadoptions/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)  
```
public class LoadOptions implements ILoadOptions
```

在加载演示文稿时，允许指定其他选项（例如格式或默认字体）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | 创建新的默认加载选项。 |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | 创建新的加载选项。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | 返回或设置要加载的演示文稿的格式。 |
| [setLoadFormat(int value)](#setLoadFormat-int-) | 返回或设置要加载的演示文稿的格式。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 返回或设置在未找到源字体时使用的常规字体。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 返回或设置在未找到源字体时使用的常规字体。 |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | 返回或设置在未找到源字体时使用的符号字体。 |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | 返回或设置在未找到源字体时使用的符号字体。 |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | 返回或设置在未找到源字体时使用的亚洲字体。 |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | 返回或设置在未找到源字体时使用的亚洲字体。 |
| [getPassword()](#getPassword--) | 获取或设置密码。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 获取或设置密码。 |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | 如果演示文稿文件受密码保护，则此属性有意义。 |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | 如果演示文稿文件受密码保护，则此属性有意义。 |
| [getWarningCallback()](#getWarningCallback--) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。 |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | 表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或内存中 BLOB 的最大字节数。 |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | 表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或内存中 BLOB 的最大字节数。 |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | 指定演示文稿使用的外部字体来源。 |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | 指定演示文稿使用的外部字体来源。 |
| [getInterruptionToken()](#getInterruptionToken--) | 用于监视中断请求的令牌。 |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 用于监视中断请求的令牌。 |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 返回或设置管理外部资源加载的回调接口。 |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 返回或设置管理外部资源加载的回调接口。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 获取电子表格的选项。 |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | 获取电子表格的选项。 |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | 返回或设置演示文稿文本的默认语言。 |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | 返回或设置演示文稿文本的默认语言。 |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | 确定在加载演示文稿时 Aspose.Slides 是否会删除所有嵌入的二进制对象。 |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | 确定在加载演示文稿时 Aspose.Slides 是否会删除所有嵌入的二进制对象。 |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

创建新的默认加载选项。

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

创建新的加载选项。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| loadFormat | int | 要加载的演示文稿的格式。 |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

返回或设置要加载的演示文稿的格式。Read/write [LoadFormat](../../com.aspose.slides/loadformat)。

**返回:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

返回或设置要加载的演示文稿的格式。Read/write [LoadFormat](../../com.aspose.slides/loadformat)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

返回或设置在未找到源字体时使用的常规字体。Read/write String.

--------------------
> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // 使用加载选项来定义默认的常规字体和亚洲字体
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // 加载演示文稿
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // 生成幻灯片缩略图
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // 生成 PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // 生成 XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

返回或设置在未找到源字体时使用的常规字体。Read/write String.

--------------------
> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // 使用加载选项来定义默认的常规字体和亚洲字体
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // 加载演示文稿
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // 生成幻灯片缩略图
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // 生成 PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // 生成 XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

返回或设置在未找到源字体时使用的符号字体。Read/write String.

**返回:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

返回或设置在未找到源字体时使用的符号字体。Read/write String.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

返回或设置在未找到源字体时使用的亚洲字体。Read/write String.

**返回:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

返回或设置在未找到源字体时使用的亚洲字体。Read/write String.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

获取或设置密码。Read/write String.

--------------------
> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 处理已解密的演示文稿
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


值：密码。

**返回:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

获取或设置密码。Read/write String.

--------------------
> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 处理已解密的演示文稿
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


值：密码。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

如果演示文稿文件受密码保护，则此属性有意义。值为 true 表示只能从加密的演示文稿文件加载文档属性，并且忽略密码。值为 false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则属性值始终被忽略。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性，并将抛出异常。Read/write boolean。

**返回:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

如果演示文稿文件受密码保护，则此属性有意义。值为 true 表示只能从加密的演示文稿文件加载文档属性，并且忽略密码。值为 false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则属性值始终被忽略。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性，并将抛出异常。Read/write boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

返回或设置一个接收警告并决定加载过程是继续还是中止的对象。Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**返回:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

返回或设置一个接收警告并决定加载过程是继续还是中止的对象。Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或内存中 BLOB 的最大字节数。这些选项旨在为特定环境或需求设定最佳的性能/内存消耗比例。

--------------------
二进制大对象（BLOB）是一种以单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示文稿本身。

**返回:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或内存中 BLOB 的最大字节数。这些选项旨在为特定环境或需求设定最佳的性能/内存消耗比例。

--------------------
二进制大对象（BLOB）是一种以单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示文稿本身。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

指定演示文稿使用的外部字体来源。这些字体在演示文稿的整个生命周期内可用，且不与其他演示文稿共享。

--------------------
> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // 处理演示文稿
>  //CustomFont1、CustomFont2 以及来自 assets\fonts 与 global\fonts 文件夹及其子文件夹的字体都可用于演示文稿
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

指定演示文稿使用的外部字体来源。这些字体在演示文稿的整个生命周期内可用，且不与其他演示文稿共享。

--------------------
> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //处理演示文稿
>  //CustomFont1、CustomFont2 以及来自 assets\fonts 与 global\fonts 文件夹及其子文件夹的字体都可用于演示文稿
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

用于监视中断请求的令牌。

--------------------
此令牌管理整个 [IPresentation](../../com.aspose.slides/ipresentation) 实例的生命周期。任何长时间运行的操作，例如加载或保存演示文稿，都将通过调用 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) 的 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 方法来中断。

**返回:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

此令牌管理整个 [IPresentation](../../com.aspose.slides/ipresentation) 实例的生命周期。任何长时间运行的操作，例如加载或保存演示文稿，都将通过调用 [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) 的 [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) 方法来中断。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

返回或设置管理外部资源加载的回调接口。Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**返回:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

返回或设置管理外部资源加载的回调接口。Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

获取电子表格的选项。例如，这些选项会影响图表公式的计算。

**返回:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

获取电子表格的选项。例如，这些选项会影响图表公式的计算。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

返回或设置演示文稿文本的默认语言。Read/write String.

--------------------
> ```
> Example:
>   
>  // 使用加载选项来定义默认文本文化
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 添加带文本的新矩形形状
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 检查第一段文字的语言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

返回或设置演示文稿文本的默认语言。Read/write String.

--------------------
> ```
> Example:
>   
>  // 使用加载选项来定义默认文本文化
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 添加带文本的新矩形形状
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 检查第一段文字的语言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

确定在加载演示文稿时 Aspose.Slides 是否会删除所有嵌入的二进制对象。

嵌入的二进制对象的类型：

Read/write  boolean .

--------------------
> ```
> 以下示例展示了如何在不加载任何嵌入的二进制对象的情况下加载演示文稿。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------
默认值为 **false** 。

**返回:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

确定在加载演示文稿时 Aspose.Slides 是否会删除所有嵌入的二进制对象。

嵌入的二进制对象的类型：

Read/write  boolean .

--------------------
> ```
> 以下示例展示了如何在不加载任何嵌入的二进制对象的情况下加载演示文稿。
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------
默认值为 **false** 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |