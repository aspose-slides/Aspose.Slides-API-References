---
title: LoadOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/loadoptions/
---
## LoadOptions 类

 在加载演示文稿时，允许指定附加选项（例如格式或默认字体）。

### LoadOptions {#LoadOptions}

| 名称 | 描述 |
| --- | --- |
| LoadOptions() | 创建新的默认加载选项。 |

**返回：**  
LoadOptions


---


### LoadOptions {#LoadOptions}

| 名称 | 描述 |
| --- | --- |
| LoadOptions(int) | 创建新的加载选项。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| loadFormat | int | 要加载的演示文稿的格式。 |

**返回：**  
LoadOptions


---


### getBlobManagementOptions {#getBlobManagementOptions}

| 名称 | 描述 |
| --- | --- |
| getBlobManagementOptions () | 表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或在内存中最大 BLOB 字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比例。二进制大对象（BLOB）是以单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示文稿本身。 |

**返回：**  
[BlobManagementOptions](../blobmanagementoptions)


---


### getDefaultAsianFont {#getDefaultAsianFont}

| 名称 | 描述 |
| --- | --- |
| getDefaultAsianFont () | 返回或设置在未找到源字体时使用的亚洲字体。读/写 String。 |

**返回：**  
String


---


### getDefaultRegularFont {#getDefaultRegularFont}

| 名称 | 描述 |
| --- | --- |
| getDefaultRegularFont () | 返回或设置在未找到源字体时使用的常规字体。读/写 String。 |

**返回：**  
String


---


### getDefaultSymbolFont {#getDefaultSymbolFont}

| 名称 | 描述 |
| --- | --- |
| getDefaultSymbolFont () | 返回或设置在未找到源字体时使用的符号字体。读/写 String。 |

**返回：**  
String


---


### getDefaultTextLanguage {#getDefaultTextLanguage}

| 名称 | 描述 |
| --- | --- |
| getDefaultTextLanguage () | 返回或设置演示文稿文本的默认语言。读/写 String。 |

**返回：**  
String


---


### getDeleteEmbeddedBinaryObjects {#getDeleteEmbeddedBinaryObjects}

| 名称 | 描述 |
| --- | --- |
| getDeleteEmbeddedBinaryObjects () | 确定 Aspose.Slides 在加载演示文稿时是否会删除所有嵌入的二进制对象。嵌入的二进制对象的类型：读/写 boolean。默认值为 false。 |

**返回：**  
boolean


---


### getDocumentLevelFontSources {#getDocumentLevelFontSources}

| 名称 | 描述 |
| --- | --- |
| getDocumentLevelFontSources () | 指定用于演示文稿的外部字体来源。这些字体在演示文稿的整个生命周期内可用，且不会与其他演示文稿共享。 |

**返回：**  
[FontSources](../fontsources)


---


### getInterruptionToken {#getInterruptionToken}

| 名称 | 描述 |
| --- | --- |
| getInterruptionToken () | 用于监视中断请求的令牌。该令牌管理整个 IPresentation 实例的生命周期。任何长期运行的操作，如加载或保存演示文稿，都将通过调用 InterruptionTokenSource#interrupt 方法来中断。 |

**返回：**  
[InterruptionToken](../interruptiontoken)


---


### getLoadFormat {#getLoadFormat}

| 名称 | 描述 |
| --- | --- |
| getLoadFormat () | 返回或设置要加载的演示文稿的格式。读/写 LoadFormat。 |

**返回：**  
int


---


### getOnlyLoadDocumentProperties {#getOnlyLoadDocumentProperties}

| 名称 | 描述 |
| --- | --- |
| getOnlyLoadDocumentProperties () | 此属性在演示文稿文件受密码保护时才有意义。true 表示仅从加密的演示文稿文件加载文档属性并忽略密码。false 表示使用正确的密码加载整个加密演示文稿。如果演示文稿未加密，则始终忽略此属性的值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。读/写 boolean。 |

**返回：**  
boolean


---


### getPassword {#getPassword}

| 名称 | 描述 |
| --- | --- |
| getPassword () | 获取或设置密码。读/写 String。值：密码。 |

**返回：**  
String


---


### getResourceLoadingCallback {#getResourceLoadingCallback}

| 名称 | 描述 |
| --- | --- |
| getResourceLoadingCallback () | 返回或设置管理外部资源加载的回调接口。读/写 IResourceLoadingCallback。 |

**返回：**  
SvgResourceResolver, ResourceLoadingAdapter


---


### getSpreadsheetOptions {#getSpreadsheetOptions}

| 名称 | 描述 |
| --- | --- |
| getSpreadsheetOptions () | 获取电子表格的选项。例如，这些选项会影响图表公式的计算。 |

**返回：**  
[SpreadsheetOptions](../spreadsheetoptions)


---


### getWarningCallback {#getWarningCallback}

| 名称 | 描述 |
| --- | --- |
| getWarningCallback () | 返回或设置接收警告并决定加载过程是继续还是中止的对象。读/写 IWarningCallback。 |

**返回：**  
IWarningCallback


---


### setBlobManagementOptions {#setBlobManagementOptions}

| 名称 | 描述 |
| --- | --- |
| setBlobManagementOptions ([BlobManagementOptions](../blobmanagementoptions)) | 表示可用于管理二进制大对象（BLOB）处理行为的选项，例如使用临时文件或在内存中最大 BLOB 字节数。这些选项旨在为特定环境或需求设置最佳的性能/内存消耗比例。二进制大对象（BLOB）是以单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示文稿本身。 |

**返回：**  
void


---


### setDefaultAsianFont {#setDefaultAsianFont}

| 名称 | 描述 |
| --- | --- |
| setDefaultAsianFont (String) | 返回或设置在未找到源字体时使用的亚洲字体。读/写 String。 |

**返回：**  
void


---


### setDefaultRegularFont {#setDefaultRegularFont}

| 名称 | 描述 |
| --- | --- |
| setDefaultRegularFont (String) | 返回或设置在未找到源字体时使用的常规字体。读/写 String。 |

**返回：**  
void


---


### setDefaultSymbolFont {#setDefaultSymbolFont}

| 名称 | 描述 |
| --- | --- |
| setDefaultSymbolFont (String) | 返回或设置在未找到源字体时使用的符号字体。读/写 String。 |

**返回：**  
void


---


### setDefaultTextLanguage {#setDefaultTextLanguage}

| 名称 | 描述 |
| --- | --- |
| setDefaultTextLanguage (String) | 返回或设置演示文稿文本的默认语言。读/写 String。 |

**返回：**  
void


---


### setDeleteEmbeddedBinaryObjects {#setDeleteEmbeddedBinaryObjects}

| 名称 | 描述 |
| --- | --- |
| setDeleteEmbeddedBinaryObjects (boolean) | 确定 Aspose.Slides 在加载演示文稿时是否会删除所有嵌入的二进制对象。嵌入的二进制对象的类型：读/写 boolean。默认值为 false。 |

**返回：**  
void


---


### setDocumentLevelFontSources {#setDocumentLevelFontSources}

| 名称 | 描述 |
| --- | --- |
| setDocumentLevelFontSources ([FontSources](../fontsources)) | 指定用于演示文稿的外部字体来源。这些字体在演示文稿的整个生命周期内可用，且不会与其他演示文稿共享。 |

**返回：**  
void


---


### setInterruptionToken {#setInterruptionToken}

| 名称 | 描述 |
| --- | --- |
| setInterruptionToken ([InterruptionToken](../interruptiontoken)) | 用于监视中断请求的令牌。该令牌管理整个 IPresentation 实例的生命周期。任何长期运行的操作，如加载或保存演示文稿，都将通过调用 InterruptionTokenSource#interrupt 方法来中断。 |

**返回：**  
void


---


### setLoadFormat {#setLoadFormat}

| 名称 | 描述 |
| --- | --- |
| setLoadFormat (int) | 返回或设置要加载的演示文稿的格式。读/写 LoadFormat。 |

**返回：**  
void


---


### setOnlyLoadDocumentProperties {#setOnlyLoadDocumentProperties}

| 名称 | 描述 |
| --- | --- |
| setOnlyLoadDocumentProperties (boolean) | 此属性在演示文稿文件受密码保护时才有意义。true 表示仅从加密的演示文稿文件加载文档属性并忽略密码。false 表示使用正确的密码加载整个加密演示文稿。如果演示文稿未加密，则始终忽略此属性的值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。读/写 boolean。 |

**返回：**  
void


---


### setPassword {#setPassword}

| 名称 | 描述 |
| --- | --- |
| setPassword (String) | 获取或设置密码。读/写 String。值：密码。 |

**返回：**  
void


---


### setResourceLoadingCallback {#setResourceLoadingCallback}

| 名称 | 描述 |
| --- | --- |
| setResourceLoadingCallback ([IResourceLoadingCallback](../iresourceloadingcallback)) | 返回或设置管理外部资源加载的回调接口。读/写 IResourceLoadingCallback。 |

**返回：**  
void


---


### setSpreadsheetOptions {#setSpreadsheetOptions}

| 名称 | 描述 |
| --- | --- |
| setSpreadsheetOptions ([SpreadsheetOptions](../spreadsheetoptions)) | 获取电子表格的选项。例如，这些选项会影响图表公式的计算。 |

**返回：**  
void


---


### setWarningCallback {#setWarningCallback}

| 名称 | 描述 |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | 返回或设置接收警告并决定加载过程是继续还是中止的对象。读/写 IWarningCallback。 |

**返回：**  
void


---