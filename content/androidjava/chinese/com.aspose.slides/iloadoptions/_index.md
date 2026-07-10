---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: 允许在加载演示文稿时指定额外的选项，例如格式或默认字体。
type: docs
url: /zh/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

允许在加载演示文稿时指定额外的选项（例如格式或默认字体）。

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
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | 如果演示文稿文件受密码保护，此属性才有意义。 |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | 如果演示文稿文件受密码保护，此属性才有意义。 |
| [getWarningCallback()](#getWarningCallback--) | 返回或设置接收警告并决定是否继续或中止加载过程的对象。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 返回或设置接收警告并决定是否继续或中止加载过程的对象。 |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | 表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或在内存中限制 BLOB 字节数。 |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | 表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或在内存中限制 BLOB 字节数。 |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | 指定演示文稿使用的外部字体来源。 |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | 指定演示文稿使用的外部字体来源。 |
| [getInterruptionToken()](#getInterruptionToken--) | 用于监视中断请求的令牌。 |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | 用于监视中断请求的令牌。 |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | 返回或设置管理外部资源加载的回调接口。 |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | 返回或设置管理外部资源加载的回调接口。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 表示可用于指定附加电子表格行为的选项。 |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | 表示可用于指定附加电子表格行为的选项。 |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | 返回或设置演示文稿文本的默认语言。 |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | 返回或设置演示文稿文本的默认语言。 |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | 确定 Aspose.Slides 在加载演示文稿时是否会删除所有嵌入的二进制对象。 |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | 确定 Aspose.Slides 在加载演示文稿时是否会删除所有嵌入的二进制对象。 |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

返回或设置要加载的演示文稿的格式。读/写 [LoadFormat](../../com.aspose.slides/loadformat)。

**返回:**  
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

返回或设置要加载的演示文稿的格式。读/写 [LoadFormat](../../com.aspose.slides/loadformat)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

返回或设置在未找到源字体时使用的常规字体。读/写 String。

**返回:**  
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

返回或设置在未找到源字体时使用的常规字体。读/写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

返回或设置在未找到源字体时使用的符号字体。读/写 String。

**返回:**  
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

返回或设置在未找到源字体时使用的符号字体。读/写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

返回或设置在未找到源字体时使用的亚洲字体。读/写 String。

**返回:**  
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

返回或设置在未找到源字体时使用的亚洲字体。读/写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

获取或设置密码。读/写 String。

值: 密码。

**返回:**  
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

获取或设置密码。读/写 String。

值: 密码。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

如果演示文稿文件受密码保护，此属性才有意义。true 表示仅从加密的演示文稿文件加载文档属性并忽略密码。false 表示使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。读/写 boolean。

**返回:**  
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

如果演示文稿文件受密码保护，此属性才有意义。true 表示仅从加密的演示文稿文件加载文档属性并忽略密码。false 表示使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。读/写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

返回或设置接收警告并决定是否继续或中止加载过程的对象。读/写 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**返回:**  
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

返回或设置接收警告并决定是否继续或中止加载过程的对象。读/写 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或在内存中限制 BLOB 字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比。

--------------------

二进制大对象（BLOB）是一种以单一实体存储的二进制数据——例如 BLOB 可以是音频、视频或演示文稿本身。

**返回:**  
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或在内存中限制 BLOB 字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比。

--------------------

二进制大对象（BLOB）是一种以单一实体存储的二进制数据——例如 BLOB 可以是音频、视频或演示文稿本身。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

指定演示文稿使用的外部字体来源。这些字体在演示文稿的整个生命周期内可用，且不与其他演示文稿共享。

**返回:**  
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

指定演示文稿使用的外部字体来源。这些字体在演示文稿的整个生命周期内可用，且不与其他演示文稿共享。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

用于监视中断请求的令牌。

--------------------

此令牌管理整个 [IPresentation](../../com.aspose.slides/ipresentation) 实例的生命周期。任何长时间运行的操作，如演示文稿加载或保存，都会通过调用 [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) 方法来中断 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)。

**返回:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

用于监视中断请求的令牌。

--------------------

此令牌管理整个 [IPresentation](../../com.aspose.slides/ipresentation) 实例的生命周期。任何长时间运行的操作，如演示文稿加载或保存，都会通过调用 [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) 方法来中断 [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

返回或设置管理外部资源加载的回调接口。读/写 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**返回:**  
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

返回或设置管理外部资源加载的回调接口。读/写 [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

表示可用于指定附加电子表格行为的选项。

**返回:**  
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

表示可用于指定附加电子表格行为的选项。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

返回或设置演示文稿文本的默认语言。读/写 String。

--------------------

> ```
> Example:
>   
>  // 使用加载选项来定义默认文本区域设置
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 添加一个带文本的新矩形形状
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 检查第一段文本的语言
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```
Returns or sets the default language for presentation text. Read/write String.

--------------------

> ```
> Example:
>   
>  // 使用加载选项来定义默认文本区域设置
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // 添加新的矩形形状并设置文本
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // 检查第一段文本的语言
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
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Determines if Aspose.Slides will delete all embedded binary objects while presentation loading.

The types of the embedded binary objects:

 *  
 *  
 *  

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
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)

确定 Aspose.Slides 在加载演示文稿时是否会删除所有嵌入的二进制对象。

嵌入的二进制对象的类型：

 *  
 *  
 *  

读/写 boolean。

The following example shows how to load the presentation without any embedded binary objects.

 LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDeleteEmbeddedBinaryObjects(true);
 Presentation pres = new Presentation("pres.ppt", loadOptions);
 try {
     pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
 } finally {
     if (pres != null) pres.dispose();
 }

默认是 **false** 。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |