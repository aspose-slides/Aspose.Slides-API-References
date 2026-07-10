---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: 表示演示文稿的属性。
type: docs
url: /zh/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

表示演示文稿的属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | 返回应用程序版本。 |
| [getNameOfApplication()](#getNameOfApplication--) | 返回或设置应用程序的名称。 |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | 返回或设置应用程序的名称。 |
| [getCompany()](#getCompany--) | 返回或设置公司属性。 |
| [setCompany(String value)](#setCompany-java.lang.String-) | 返回或设置公司属性。 |
| [getManager()](#getManager--) | 返回或设置管理员属性。 |
| [setManager(String value)](#setManager-java.lang.String-) | 返回或设置管理员属性。 |
| [getPresentationFormat()](#getPresentationFormat--) | 返回或设置演示文稿的预期格式。 |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | 返回或设置演示文稿的预期格式。 |
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
| [getLastPrinted()](#getLastPrinted--) | 返回演示文稿上次打印的日期。 |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | 返回演示文稿上次打印的日期。 |
| [getLastSavedBy()](#getLastSavedBy--) | 返回或设置最后修改演示文稿的人的名称。 |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | 返回或设置最后修改演示文稿的人的名称。 |
| [getRevisionNumber()](#getRevisionNumber--) | 返回或设置演示文稿的修订号。 |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | 返回或设置演示文稿的修订号。 |
| [getContentStatus()](#getContentStatus--) | 返回或设置演示文稿的内容状态。 |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | 返回或设置演示文稿的内容状态。 |
| [getContentType()](#getContentType--) | 返回或设置演示文稿的内容类型。 |
| [setContentType(String value)](#setContentType-java.lang.String-) | 返回或设置演示文稿的内容类型。 |
| [getHyperlinkBase()](#getHyperlinkBase--) | 返回或设置 HyperlinkBase 文档属性。 |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | 返回或设置 HyperlinkBase 文档属性。 |
| [getScaleCrop()](#getScaleCrop--) | 指示文档缩略图的显示模式。 |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | 指示文档缩略图的显示模式。 |
| [getLinksUpToDate()](#getLinksUpToDate--) | 指示文档中的超链接是否为最新。 |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | 指示文档中的超链接是否为最新。 |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | 指定此部分中的一个或多个超链接已由生产者专门在此部分更新。 |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | 指定此部分中的一个或多个超链接已由生产者专门在此部分更新。 |
| [getSlides()](#getSlides--) | 指定演示文稿文档中的幻灯片总数。 |
| [getHiddenSlides()](#getHiddenSlides--) | 指定演示文稿文档中隐藏的幻灯片数量。 |
| [getNotes()](#getNotes--) | 指定包含备注的演示文稿幻灯片数量。 |
| [getParagraphs()](#getParagraphs--) | 如果适用，指定文档中找到的段落总数。 |
| [getWords()](#getWords--) | 指定文档中包含的单词总数。 |
| [getMultimediaClips()](#getMultimediaClips--) | 指定文档中存在的音频或视频剪辑的总数。 |
| [getTitlesOfParts()](#getTitlesOfParts--) | 指定每个文档部分的标题。 |
| [getHeadingPairs()](#getHeadingPairs--) | 指示文档部分的分组及每组的部分数量。 |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | 返回集合中实际包含的自定义属性数量。 |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | 返回指定索引处的自定义属性名称。 |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | 删除与指定名称关联的自定义属性。 |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | 检查是否存在具有指定名称的自定义属性。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 返回或设置与指定名称关联的自定义属性。 |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 返回或设置与指定名称关联的自定义属性。 |
| [clearCustomProperties()](#clearCustomProperties--) | 删除所有自定义属性。 |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | 清除并为所有内置属性设置默认值。 |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Sets a named boolean custom property. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Sets a named integer custom property. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Sets a named DateTime custom property. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Sets a named string custom property. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Sets a named float custom property. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Sets a named double custom property. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

返回应用程序版本。只读 String。

**返回：**  
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

返回或设置应用程序的名称。读写 String。

**返回：**  
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

返回或设置应用程序的名称。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

返回或设置公司属性。读写 String。

**返回：**  
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

返回或设置公司属性。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

返回或设置管理员属性。读写 String。

**返回：**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

返回或设置管理员属性。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

返回或设置演示文稿的预期格式。读写 String。

**返回：**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

返回或设置演示文稿的预期格式。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

确定演示文稿是否在多个人之间共享。读写 boolean。

**返回：**  
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

确定演示文稿是否在多个人之间共享。读写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

返回或设置应用程序的模板。读写 String。

**返回：**  
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

返回或设置应用程序的模板。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

演示文稿的总编辑时间。读写 double。

**返回：**  
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

演示文稿的总编辑时间。读写 double。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

返回或设置演示文稿的标题。读写 String。

**返回：**  
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

返回或设置演示文稿的标题。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

返回或设置演示文稿的主题。读写 String。

**返回：**  
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

返回或设置演示文稿的主题。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

返回或设置演示文稿的作者。读写 String。

**返回：**  
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

返回或设置演示文稿的作者。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

返回或设置演示文稿的关键字。读写 String。

**返回：**  
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

返回或设置演示文稿的关键字。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

返回或设置演示文稿的注释。读写 String。

**返回：**  
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

返回或设置演示文稿的注释。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

返回或设置演示文稿的类别。读写 String。

**返回：**  
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

返回或设置演示文稿的类别。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

返回演示文稿的创建日期。值为 UTC。读写 java.util.Date。

**返回：**  
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

设置演示文稿的创建日期。值为 UTC。读写 java.util.Date。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

返回演示文稿的最近修改日期。值为 UTC。只读（在 Presentation.DocumentProperties 情况下，因为在 IPresentation 对象保存过程中会内部更新）。可以通过方法 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) 返回的 DocumentProperties 实例进行更改。请参阅 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 方法摘要中的示例。

**返回：**  
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

设置演示文稿的最近修改日期。值为 UTC。只读（在 Presentation.DocumentProperties 情况下，因为在 IPresentation 对象保存过程中会内部更新）。可以通过方法 [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) 返回的 DocumentProperties 实例进行更改。请参阅 [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) 方法摘要中的示例。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

返回演示文稿上次打印的日期。读写 java.util.Date。

**返回：**  
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

返回演示文稿上次打印的日期。读写 java.util.Date。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

返回或设置最后修改演示文稿的人的名称。读写 String。

**返回：**  
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

返回或设置最后修改演示文稿的人的名称。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

返回或设置演示文稿的修订号。读写 int。

**返回：**  
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

返回或设置演示文稿的修订号。读写 int。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

返回或设置演示文稿的内容状态。读写 String。

**返回：**  
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

返回或设置演示文稿的内容状态。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

返回或设置演示文稿的内容类型。读写 String。

**返回：**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

返回或设置演示文稿的内容类型。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

返回或设置 HyperlinkBase 文档属性。读写 String。

**返回：**  
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

返回或设置 HyperlinkBase 文档属性。读写 String。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

指示文档缩略图的显示模式。将此元素设置为 **true** 以启用文档缩略图的缩放以适应显示。将此元素设置为 **false** 以启用对文档缩略图的裁剪，仅显示适合显示的部分。读写 boolean。

**返回：**  
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

指示文档缩略图的显示模式。将此元素设置为 **true** 以启用文档缩略图的缩放以适应显示。将此元素设置为 **false** 以启用对文档缩略图的裁剪，仅显示适合显示的部分。读写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

指示文档中的超链接是否为最新。将此元素设置为 **true** 以指示超链接已更新。将此元素设置为 **false** 以指示超链接已过时。读写 boolean。

**返回：**  
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

指示文档中的超链接是否为最新。将此元素设置为 **true** 以指示超链接已更新。将此元素设置为 **false** 以指示超链接已过时。读写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

指定此部分中的一个或多个超链接已由生产者专门在此部分更新。下一个打开此文档的生产者应使用此部分中指定的新超链接更新超链接关系。读写 boolean。

**返回：**  
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

指定此部分中的一个或多个超链接已由生产者专门在此部分更新。下一个打开此文档的生产者应使用此部分中指定的新超链接更新超链接关系。读写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

指定演示文稿文档中的幻灯片总数。只读 int。

**返回：**  
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

指定演示文稿文档中隐藏的幻灯片数量。只读 int。

**返回：**  
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

指定包含备注的演示文稿幻灯片数量。只读 int。

**返回：**  
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

指定文档中找到的段落总数（如果适用）。只读 int。

**返回：**  
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

指定文档中包含的单词总数。只读 int。

**返回：**  
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

指定文档中存在的音频或视频剪辑的总数。只读 int。

**返回：**  
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

指定每个文档部分的标题。这些部分不是文档部分，而是文档章节的概念表示。只读 String[]。

**返回：**  
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

指示文档部分的分组及每组的部分数量。只读 IHeadingPair[]。

**返回：**  
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

返回集合中实际包含的自定义属性数量。只读 int。

**返回：**  
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

返回指定索引处的自定义属性名称。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的自定义属性的零基索引。 |

**返回：**  
java.lang.String - 在指定索引处的自定义属性名称。

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

删除与指定名称关联的自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的自定义属性的名称。 |

**返回：**  
boolean - 如果属性已删除返回 true，否则返回 false。

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract 



Sorry, this request is 


```

检查是否存在具有指定名称的自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要检查的自定义属性的名称。 |

**返回：**  
boolean - 如果属性存在返回 true，否则返回 false。

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

返回或设置与指定名称关联的自定义属性。读写 Object。

> Value can be **int**, **float**, **double**, **String**, **boolean** or **Date**.

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String |  |

**返回：**  
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

返回或设置与指定名称关联的自定义属性。读写 Object。

> Value can be **int**, **float**, **double**, **String**, **boolean** or **Date**.

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

删除所有自定义属性。

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

清除并为所有内置属性设置默认值。

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

从自定义属性中获取指定名称的布尔值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性的名称 |
| value | boolean[] | 自定义属性值 |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

从自定义属性中获取指定名称的整数值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性的名称 |
| value | int[] | 自定义属性值 |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

从自定义属性中获取指定名称的 DateTime 值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性的名称 |
| value | java.util.Date[] | 自定义属性值 |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

从自定义属性中获取指定名称的字符串值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性的名称 |
| value | java.lang.String[] | 自定义属性值 |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

从自定义属性中获取指定名称的 float 值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性的名称 |
| value | float[] | 自定义属性值 |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

从自定义属性中获取指定名称的 double 值。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要获取的自定义属性的名称。 |
| value | double[] | 自定义属性值 |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

设置指定名称的布尔自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性的名称 |
| value | boolean | 自定义属性值 |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

设置指定名称的整数自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性的名称 |
| value | int | 自定义属性值 |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

设置指定名称的 DateTime 自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性的名称 |
| value | java.util.Date | 自定义属性值 |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

设置指定名称的字符串自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性的名称 |
| value | java.lang.String | 自定义属性值 |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

设置指定名称的 float 自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性的名称 |
| value | float | 自定义属性值 |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

设置指定名称的 double 自定义属性。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要设置的自定义属性的名称 |
| value | double | 自定义属性值 |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

从自定义文档属性（Microsoft Information Protection SDK 元数据）获取敏感度标签数组。

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