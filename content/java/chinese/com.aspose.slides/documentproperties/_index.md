---
title: DocumentProperties
second_title: Aspose.Slides for Java API 参考
description: 表示演示文稿的属性。
type: docs
url: /zh/com.aspose.slides/documentproperties/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

表示演示文稿的属性。

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // 实例化表示演示文稿的 Presentation 类
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // 创建与演示文稿关联的 IDocumentProperties 对象的引用
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // 显示内置属性
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // 实例化表示演示文稿的 Presentation 类
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // 创建与演示文稿关联的 IDocumentProperties 对象的引用
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // 设置内置属性
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // 将演示文稿保存到文件
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | 初始化 [DocumentProperties](../../com.aspose.slides/documentproperties) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | 返回应用程序版本。 |
| [getNameOfApplication()](#getNameOfApplication--) | 返回或设置应用程序的名称。 |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | 返回或设置应用程序的名称。 |
| [getCompany()](#getCompany--) | 返回或设置公司属性。 |
| [setCompany(String value)](#setCompany-java.lang.String-) | 返回或设置公司属性。 |
| [getManager()](#getManager--) | 返回或设置经理属性。 |
| [setManager(String value)](#setManager-java.lang.String-) | 返回或设置经理属性。 |
| [getPresentationFormat()](#getPresentationFormat--) | 返回或设置演示文稿的目标格式。 |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | 返回或设置演示文稿的目标格式。 |
| [getSharedDoc()](#getSharedDoc--) | 确定演示文稿是否在多个人之间共享。 |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | 确定演示文稿是否在多个人之间共享。 |
| [getApplicationTemplate()](#getApplicationTemplate--) | 返回或设置应用程序的模板。 |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | 返回或设置应用程序的模板。 |
| [getTotalEditingTime()](#getTotalEditingTime--) | 演示文稿的总编辑时间。 |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | 演示文稿的总编辑时间。 |
| [getTitle()](#getTitle--) | 返回或设置演示文稿的标题。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 返回或设置演示文稿的标题。 |
| [getSubject()](#getSubject--) | 返回或设置演示文稿的主题。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 返回或设置演示文稿的主题。 |
| [getAuthor()](#getAuthor--) | 返回或设置演示文稿的作者。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 返回或设置演示文稿的作者。 |
| [getKeywords()](#getKeywords--) | 返回或设置演示文稿的关键字。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 返回或设置演示文稿的关键字。 |
| [getComments()](#getComments--) | 返回或设置演示文稿的注释。 |
| [setComments(String value)](#setComments-java.lang.String-) | 返回或设置演示文稿的注释。 |
| [getCategory()](#getCategory--) | 返回或设置演示文稿的类别。 |
| [setCategory(String value)](#setCategory-java.lang.String-) | 返回或设置演示文稿的类别。 |
| [getCreatedTime()](#getCreatedTime--) | 返回演示文稿的创建日期。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | 返回演示文稿的创建日期。 |
| [getLastSavedTime()](#getLastSavedTime--) | 返回演示文稿的最近修改日期。 |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | 返回演示文稿的最近修改日期。 |
| [getLastPrinted()](#getLastPrinted--) | 返回演示文稿上一次打印的日期。 |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | 返回演示文稿上一次打印的日期。 |
| [getLastSavedBy()](#getLastSavedBy--) | 返回或设置最后修改演示文稿的人的姓名。 |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | 返回或设置最后修改演示文稿的人的姓名。 |
| [getRevisionNumber()](#getRevisionNumber--) | 返回或设置演示文稿的修订号。 |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | 返回或设置演示文稿的修订号。 |
| [getContentStatus()](#getContentStatus--) | 返回或设置演示文稿的内容状态。 |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | 返回或设置演示文稿的内容状态。 |
| [getContentType()](#getContentType--) | 返回或设置演示文稿的内容类型。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | 返回或设置演示文稿的内容类型。 |
| [getHyperlinkBase()](#getHyperlinkBase--) | 返回或设置文档的 HyperlinkBase 属性。 |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | 返回或设置文档的 HyperlinkBase 属性。 |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | 返回集合中实际包含的自定义属性数量。 |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 返回指定索引处的自定义属性名称。 |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 移除与指定名称关联的自定义属性。 |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 检查是否存在指定名称的自定义属性。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 返回或设置与指定名称关联的自定义属性。 |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 返回或设置与指定名称关联的自定义属性。 |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | 设置具名布尔自定义属性。 |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | 设置具名整数自定义属性。 |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | 设置具名 DateTime 自定义属性。 |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | 设置具名字符串自定义属性。 |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | 设置具名浮点数自定义属性。 |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | 设置具名双精度自定义属性。 |
| [clearCustomProperties()](#clearCustomProperties--) | 移除所有自定义属性。 |
| [getSensitivityLabels()](#getSensitivityLabels--) | 从自定义文档属性获取敏感度标签数组（Microsoft Information Protection SDK 元数据）。 |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | 清除并为所有内置属性设置默认值。 |
| [getScaleCrop()](#getScaleCrop--) | 指示文档缩略图的显示模式。 |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | 指示文档缩略图的显示模式。 |
| [getLinksUpToDate()](#getLinksUpToDate--) | 指示文档中的超链接是否为最新。 |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | 指示文档中的超链接是否为最新。 |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | 指定此部分中的一个或多个超链接仅由生成者在此部分更新。 |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | 指定此部分中的一个或多个超链接仅由生成者在此部分更新。 |
| [getSlides()](#getSlides--) | 返回演示文稿文档中的幻灯片总数。 |
| [getHiddenSlides()](#getHiddenSlides--) | 返回演示文稿文档中隐藏的幻灯片数量。 |
| [getNotes()](#getNotes--) | 返回包含备注的幻灯片数量。 |
| [getParagraphs()](#getParagraphs--) | 如果适用，返回文档中找到的段落总数。 |
| [getWords()](#getWords--) | 返回文档中包含的单词总数。 |
| [getMultimediaClips()](#getMultimediaClips--) | 返回文档中存在的音频或视频剪辑的总数。 |
| [getTitlesOfParts()](#getTitlesOfParts--) | 指定每个文档部分的标题。 |
| [getHeadingPairs()](#getHeadingPairs--) | 指示文档部分的分组及每组的部分数量。 |
| [deepClone()](#deepClone--) | 克隆当前对象 |
| [cloneT()](#cloneT--) | 克隆当前对象 |

### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

初始化 [DocumentProperties](../../com.aspose.slides/documentproperties) 类的新实例。

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

返回应用程序版本。只读 String。

**返回：**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

返回或设置应用程序的名称。读写 String。

**返回：**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

返回或设置应用程序的名称。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

返回或设置公司属性。读写 String。

**返回：**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

返回或设置公司属性。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

返回或设置经理属性。读写 String。

**返回：**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

返回或设置经理属性。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

返回或设置演示文稿的目标格式。读写 String。

**返回：**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

返回或设置演示文稿的目标格式。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

确定演示文稿是否在多个人之间共享。读写 boolean。

**返回：**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

确定演示文稿是否在多个人之间共享。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

返回或设置应用程序的模板。读写 String。

**返回：**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

返回或设置应用程序的模板。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

演示文稿的总编辑时间。读写 double。

**返回：**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

演示文稿的总编辑时间。读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

返回或设置演示文稿的标题。读写 String。

**返回：**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

返回或设置演示文稿的标题。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

返回或设置演示文稿的主题。读写 String。

**返回：**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

返回或设置演示文稿的主题。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

返回或设置演示文稿的作者。读写 String。

**返回：**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

返回或设置演示文稿的作者。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

返回或设置演示文稿的关键字。读写 String。

**返回：**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

返回或设置演示文稿的关键字。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

返回或设置演示文稿的注释。读写 String。

**返回：**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

返回或设置演示文稿的注释。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

返回或设置演示文稿的类别。读写 String。

**返回：**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

返回或设置演示文稿的类别。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
返回演示文稿创建的日期。值为 UTC。可读写 java.util.Date。

**返回：**  
java.util.Date  
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}  
```
public final void setCreatedTime(Date value)
```

返回演示文稿创建的日期。值为 UTC。可读写 java.util.Date。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}  
```
public final Date getLastSavedTime()
```

返回演示文稿上次修改的日期。值为 UTC。只读（针对 Presentation.DocumentProperties，因为在 IPresentation 对象保存过程中会内部更新）。可以通过方法 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) 返回的 DocumentProperties 实例进行更改。请参阅 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 方法摘要中的示例。

**返回：**  
java.util.Date  
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}  
```
public final void setLastSavedTime(Date value)
```

返回演示文稿上次修改的日期。值为 UTC。只读（针对 Presentation.DocumentProperties，因为在 IPresentation 对象保存过程中会内部更新）。可以通过方法 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) 返回的 DocumentProperties 实例进行更改。请参阅 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 方法摘要中的示例。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}  
```
public final Date getLastPrinted()
```

返回演示文稿上次打印的日期。可读写 java.util.Date。

**返回：**  
java.util.Date  
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}  
```
public final void setLastPrinted(Date value)
```

返回演示文稿上次打印的日期。可读写 java.util.Date。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}  
```
public final String getLastSavedBy()
```

返回或设置上次修改演示文稿的人员姓名。可读写 String。

**返回：**  
java.lang.String  
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}  
```
public final void setLastSavedBy(String value)
```

返回或设置上次修改演示文稿的人员姓名。可读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}  
```
public final int getRevisionNumber()
```

返回或设置演示文稿的修订号。可读写 int。

**返回：**  
int  
### setRevisionNumber(int value) {#setRevisionNumber-int-}  
```
public final void setRevisionNumber(int value)
```

返回或设置演示文稿的修订号。可读写 int。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}  
```
public final String getContentStatus()
```

返回或设置演示文稿的内容状态。可读写 String。

**返回：**  
java.lang.String  
### setContentStatus(String value) {#setContentStatus-java.lang.String-}  
```
public final void setContentStatus(String value)
```

返回或设置演示文稿的内容状态。可读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}  
```
public final String getContentType()
```

返回或设置演示文稿的内容类型。可读写 String。

**返回：**  
java.lang.String  
### setContentType(String value) {#setContentType-java.lang.String-}  
```
public final void setContentType(String value)
```

返回或设置演示文稿的内容类型。可读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}  
```
public final String getHyperlinkBase()
```

返回或设置 HyperlinkBase 文档属性。可读写 String。

**返回：**  
java.lang.String  
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}  
```
public final void setHyperlinkBase(String value)
```

返回或设置 HyperlinkBase 文档属性。可读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}  
```
public final int getCountOfCustomProperties()
```

返回集合中实际包含的自定义属性数量。只读 int。

**返回：**  
int  
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}  
```
public final String getCustomPropertyName(int index)
```

返回指定索引处的自定义属性名称。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的自定义属性的零基索引。 |

**返回：**  
java.lang.String - 指定索引处的自定义属性名称。  
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}  
```
public final boolean removeCustomProperty(String name)
```

移除具有指定名称的自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要移除的自定义属性的名称。 |

**返回：**  
boolean - 若属性被移除返回 true，否则返回 false。  
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}  
```
public final boolean containsCustomProperty(String name)
```

检查是否存在具有指定名称的自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要检查的自定义属性的名称。 |

**返回：**  
boolean - 若属性存在返回 true，否则返回 false。  
### get_Item(String name) {#get-Item-java.lang.String-}  
```
public final Object get_Item(String name)
```

返回或设置与指定名称关联的自定义属性。可读写 Object。

值可以是 **int**、**float**、**String**、**boolean** 或 **Date**。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String |  |

**返回：**  
java.lang.Object  
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}  
```
public final void set_Item(String name, Object value)
```

返回或设置与指定名称关联的自定义属性。可读写 Object。

值可以是 **int**、**float**、**String**、**boolean** 或 **Date**。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}  
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

获取自定义属性中的布尔值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性名称 |
| value | boolean[] | 自定义属性值 |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}  
```
public final void getCustomPropertyValue(String name, int[] value)
```

获取自定义属性中的整数值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性名称 |
| value | int[] | 自定义属性值 |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}  
```
public final void getCustomPropertyValue(String name, Date[] value)
```

获取自定义属性中的 DateTime 值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性名称 |
| value | java.util.Date[] | 自定义属性值 |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}  
```
public final void getCustomPropertyValue(String name, String[] value)
```

获取自定义属性中的字符串值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性名称 |
| value | java.lang.String[] | 自定义属性值 |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}  
```
public final void getCustomPropertyValue(String name, float[] value)
```

获取自定义属性中的浮点值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性名称 |
| value | float[] | 自定义属性值 |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}  
```
public final void getCustomPropertyValue(String name, double[] value)
```

获取自定义属性中的 double 值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性名称。 |
| value | double[] | 自定义属性值 |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}  
```
public final void setCustomPropertyValue(String name, boolean value)
```

设置指定名称的布尔自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性名称 |
| value | boolean | 自定义属性值 |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}  
```
public final void setCustomPropertyValue(String name, int value)
```

设置指定名称的整数自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性名称 |
| value | int | 自定义属性值 |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}  
```
public final void setCustomPropertyValue(String name, Date value)
```

设置指定名称的 DateTime 自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性名称 |
| value | java.util.Date | 自定义属性值 |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}  
```
public final void setCustomPropertyValue(String name, String value)
```

设置指定名称的字符串自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性名称 |
| value | java.lang.String | 自定义属性值 |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}  
```
public final void setCustomPropertyValue(String name, float value)
```

设置指定名称的浮点自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性名称 |
| value | float | 自定义属性值 |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}  
```
public final void setCustomPropertyValue(String name, double value)
```

设置指定名称的 double 自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性名称 |
| value | double | 自定义属性值 |

### clearCustomProperties() {#clearCustomProperties--}  
```
public final void clearCustomProperties()
```

移除所有自定义属性。

### getSensitivityLabels() {#getSensitivityLabels--}  
```
public final ISensitivityLabel[] getSensitivityLabels()
```

获取自定义文档属性中的敏感度标签数组（Microsoft Information Protection SDK 元数据）。

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**  
com.aspose.slides.ISensitivityLabel[]  
### clearBuiltInProperties() {#clearBuiltInProperties--}  
```
public final void clearBuiltInProperties()
```

清除并为所有内置属性设置默认值。

### getScaleCrop() {#getScaleCrop--}  
```
public final boolean getScaleCrop()
```

指示文档缩略图的显示模式。将此元素设置为 **true** 可启用缩放文档缩略图以适应显示；将此元素设置为 **false** 可启用裁剪文档缩略图，仅显示适合显示的部分。可读写 boolean。

**返回：**  
boolean  
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}  
```
public final void setScaleCrop(boolean value)
```

指示文档缩略图的显示模式。将此元素设置为 **true** 可启用缩放文档缩略图以适应显示；将此元素设置为 **false** 可启用裁剪文档缩略图，仅显示适合显示的部分。可读写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}  
```
public final boolean getLinksUpToDate()
```

指示文档中的超链接是否为最新。将此元素设置为 **true** 表示超链接已更新；将此元素设置为 **false** 表示超链接已过期。可读写 boolean。

**返回：**  
boolean  
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}  
```
public final void setLinksUpToDate(boolean value)
```
指示文档中的超链接是否为最新。将此元素设为 **true** 表示超链接已更新。将此元素设为 **false** 表示超链接已过时。读写 boolean。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

指定此部分中的一个或多个超链接仅由生产者在此部分更新。下一个打开此文档的生产者应使用此部分中指定的新超链接更新超链接关系。读写 boolean。

**返回值：**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

指定此部分中的一个或多个超链接仅由生产者在此部分更新。下一个打开此文档的生产者应使用此部分中指定的新超链接更新超链接关系。读写 boolean。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

返回演示文稿文档中的幻灯片总数。只读 int。

**返回值：**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

返回演示文稿文档中隐藏的幻灯片数。只读 int。

**返回值：**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

返回包含备注的幻灯片数量。只读 int。

**返回值：**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

返回文档（如果适用）中找到的段落总数。只读 int。

**返回值：**
int
### getWords() {#getWords--}
```
public final int getWords()
```

返回文档中包含的单词总数。只读 int。

**返回值：**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

返回文档中存在的声音或视频剪辑的总数。只读 int。

**返回值：**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

指定每个文档部分的标题。这些部分不是文档部分，而是文档章节的概念表示。只读 String[]。

**返回值：**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

指示文档部分的分组以及每组中的部分数量。只读 IHeadingPair[]。

**返回值：**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

克隆当前对象

**返回值：**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

克隆当前对象

**返回值：**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone