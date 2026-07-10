---
title: LoadOptions
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 允许在加载演示文稿时指定附加选项，例如格式或默认字体。
type: docs
url: /zh/com.aspose.slides/loadoptions/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

在加载演示文稿时，允许指定附加选项（例如格式或默认字体）。
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
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | 当演示文稿文件受密码保护时，此属性才有意义。 |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | 当演示文稿文件受密码保护时，此属性才有意义。 |
| [getWarningCallback()](#getWarningCallback--) | 返回或设置接收警告并决定加载过程是继续还是中止的对象。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 返回或设置接收警告并决定加载过程是继续还是中止的对象。 |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | 表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或内存中最大 BLOB 字节数。 |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | 表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或内存中最大 BLOB 字节数。 |
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
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | 确定 Aspose.Slides 在加载演示文稿时是否删除所有嵌入的二进制对象。 |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | 确定 Aspose.Slides 在加载演示文稿时是否删除所有嵌入的二进制对象。 |
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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| loadFormat | int | 要加载的演示文稿的格式。 |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

返回或设置要加载的演示文稿的格式。 读取/写入 [LoadFormat](../../com.aspose.slides/loadformat)。

**返回值：**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

返回或设置要加载的演示文稿的格式。 读取/写入 [LoadFormat](../../com.aspose.slides/loadformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

返回或设置在未找到源字体时使用的常规字体。 读取/写入 String。

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
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // 生成 PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // 生成 XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Returns or sets Regular font used in case source font is not found. Read/write String.

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
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // 生成 PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // 生成 XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Returns or sets Symbol font used in case source font is not found. Read/write String.

**Returns:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Returns or sets Symbol font used in case source font is not found. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Returns or sets Asian font used in case source font is not found. Read/write String.

**Returns:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Returns or sets Asian font used in case source font is not found. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Gets or sets the password. Read/write String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 在解密的演示文稿上进行操作
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Value: The password.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Gets or sets the password. Read/write String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // 在解密的演示文稿上工作
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Value: The password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean.

**Returns:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returns:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

表示可用于管理二进制大对象 (BLOB) 处理行为的选项，例如使用临时文件或在内存中限制 BLOB 的最大字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比例。

--------------------

二进制大对象 (BLOB) 是以单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示文稿本身。

**Returns:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //对演示文稿进行操作
>  //CustomFont1、CustomFont2 以及来自 assets\\fonts 和 global\\fonts 文件夹及其子文件夹的字体对演示文稿可用
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // 对演示文稿进行操作
>  // CustomFont1、CustomFont2 以及来自 assets\\fonts 和 global\\fonts 文件夹及其子文件夹的字体对演示文稿可用
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

The token to monitor for interruption requests.

--------------------

This token manages the whole [IPresentation](../../com.aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) method of the [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Returns:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

The token to monitor for interruption requests.

--------------------

This token manages the whole [IPresentation](../../com.aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) method of the [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Returns or sets callback interface which manages external resources loading. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Returns:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Returns or sets callback interface which manages external resources loading. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Gets options for spreadsheets. For example, these options affect calculating formulas for charts.

**Returns:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Gets options for spreadsheets. For example, these options affect calculating formulas for charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Returns or sets the default language for presentation text. Read/write String.

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
>      // 检查第一段的语言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```
Returns or sets the default language for presentation text. Read/write String.

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
>      // 检查第一段的语言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Determines if Aspose.Slides will delete all embedded binary objects while presentation loading.

The types of the embedded binary objects:

Read/write  boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

Default is  **false** .

**Returns:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)

确定 Aspose.Slides 在加载演示文稿时是否删除所有嵌入的二进制对象。

嵌入的二进制对象的类型：

读取/写入 boolean 。

--------------------

> ```
> 以下示例展示了如何在不包含任何嵌入二进制对象的情况下加载演示文稿。
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

默认是 **false** 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |