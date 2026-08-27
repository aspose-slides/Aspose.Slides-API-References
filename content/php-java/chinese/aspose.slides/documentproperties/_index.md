---
title: DocumentProperties
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/documentproperties/
---
## DocumentProperties 类

表示演示文稿的属性。

### DocumentProperties {#DocumentProperties}

| Name | Description |
| --- | --- |
| DocumentProperties() | 初始化类 DocumentProperties 的新实例。 |

**返回：**  
DocumentProperties

---

### clearBuiltInProperties {#clearBuiltInProperties}

| Name | Description |
| --- | --- |
| clearBuiltInProperties () | 清除并为所有 builtIn 属性设置默认值。 |

**返回：**  
void

---

### clearCustomProperties {#clearCustomProperties}

| Name | Description |
| --- | --- |
| clearCustomProperties () | 移除所有自定义属性。 |

**返回：**  
void

---

### cloneT {#cloneT}

| Name | Description |
| --- | --- |
| cloneT () | 克隆当前对象 |

**返回：**  
[DocumentProperties](../documentproperties)

---

### containsCustomProperty {#containsCustomProperty}

| Name | Description |
| --- | --- |
| containsCustomProperty (String) | 检查是否存在具有指定名称的自定义属性。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要检查的自定义属性的名称。 |

**返回：**  
boolean

---

### deepClone {#deepClone}

| Name | Description |
| --- | --- |
| deepClone () | 克隆当前对象 |

**返回：**  
Object

---

### getAppVersion {#getAppVersion}

| Name | Description |
| --- | --- |
| getAppVersion () | 返回应用程序版本。只读 String。 |

**返回：**  
String

---

### getApplicationTemplate {#getApplicationTemplate}

| Name | Description |
| --- | --- |
| getApplicationTemplate () | 返回或设置应用程序的模板。可读写 String。 |

**返回：**  
String

---

### getAuthor {#getAuthor}

| Name | Description |
| --- | --- |
| getAuthor () | 返回或设置演示文稿的作者。可读写 String。 |

**返回：**  
String

---

### getCategory {#getCategory}

| Name | Description |
| --- | --- |
| getCategory () | 返回或设置演示文稿的类别。可读写 String。 |

**返回：**  
String

---

### getComments {#getComments}

| Name | Description |
| --- | --- |
| getComments () | 返回或设置演示文稿的注释。可读写 String。 |

**返回：**  
String

---

### getCompany {#getCompany}

| Name | Description |
| --- | --- |
| getCompany () | 返回或设置公司属性。可读写 String。 |

**返回：**  
String

---

### getContentStatus {#getContentStatus}

| Name | Description |
| --- | --- |
| getContentStatus () | 返回或设置演示文稿的内容状态。可读写 String。 |

**返回：**  
String

---

### getContentType {#getContentType}

| Name | Description |
| --- | --- |
| getContentType () | 返回或设置演示文稿的内容类型。可读写 String。 |

**返回：**  
String

---

### getCountOfCustomProperties {#getCountOfCustomProperties}

| Name | Description |
| --- | --- |
| getCountOfCustomProperties () | 返回集合中实际包含的自定义属性数量。只读 int。 |

**返回：**  
int

---

### getCreatedTime {#getCreatedTime}

| Name | Description |
| --- | --- |
| getCreatedTime () | 返回演示文稿创建的日期。值为 UTC。可读写 java.util.Date。 |

**返回：**  
Date

---

### getCustomPropertyName {#getCustomPropertyName}

| Name | Description |
| --- | --- |
| getCustomPropertyName (int) | 返回指定索引处的自定义属性名称。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的自定义属性的零基索引。 |

**返回：**  
String

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 索引小于零。索引大于等于 Count。 |

---

### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, boolean[]) | 从自定义属性中获取具名布尔值。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要获取的自定义属性的名称 |
| value | boolean[] | 自定义属性值 |

**返回：**  
void

---

### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, int[]) | 从自定义属性中获取具名整数值。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要获取的自定义属性的名称 |
| value | int[] | 自定义属性值 |

**返回：**  
void

---

### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, java.util.Date[]) | 从自定义属性中获取具名 DateTime 值。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要获取的自定义属性的名称 |
| value | java.util.Date[] | 自定义属性值 |

**返回：**  
void

---

### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, java.lang.String[]) | 从自定义属性中获取具名字符串值。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要获取的自定义属性的名称 |
| value | java.lang.String[] | 自定义属性值 |

**返回：**  
void

---

### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, float[]) | 从自定义属性中获取具名浮点值。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要获取的自定义属性的名称 |
| value | float[] | 自定义属性值 |

**返回：**  
void

---

### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, double[]) | 从自定义属性中获取具名双精度值。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要获取的自定义属性的名称 |
| value | double[] | 自定义属性值 |

**返回：**  
void

---

### getHeadingPairs {#getHeadingPairs}

| Name | Description |
| --- | --- |
| getHeadingPairs () | 指示文档部分的分组以及每组的部分数量。只读 IHeadingPair[]. |

**返回：**  
[HeadingPair](../headingpair)

---

### getHiddenSlides {#getHiddenSlides}

| Name | Description |
| --- | --- |
| getHiddenSlides () | 返回演示文稿文档中隐藏的幻灯片数量。只读 int。 |

**返回：**  
int

---

### getHyperlinkBase {#getHyperlinkBase}

| Name | Description |
| --- | --- |
| getHyperlinkBase () | 返回或设置 HyperlinkBase 文档属性。可读写 String。 |

**返回：**  
String

---

### getHyperlinksChanged {#getHyperlinksChanged}

| Name | Description |
| --- | --- |
| getHyperlinksChanged () | 指定此部分中的一个或多个超链接已由生产者在此部分专门更新。下一个打开此文档的生产者应使用此部分中指定的新超链接更新超链接关系。可读写 boolean。 |

**返回：**  
boolean

---

### getKeywords {#getKeywords}

| Name | Description |
| --- | --- |
| getKeywords () | 返回或设置演示文稿的关键字。可读写 String。 |

**返回：**  
String

---

### getLastPrinted {#getLastPrinted}

| Name | Description |
| --- | --- |
| getLastPrinted () | 返回演示文稿上次打印的日期。可读写 java.util.Date。 |

**返回：**  
Date

---

### getLastSavedBy {#getLastSavedBy}

| Name | Description |
| --- | --- |
| getLastSavedBy () | 返回或设置最后修改演示文稿的人员姓名。可读写 String。 |

**返回：**  
String

---

### getLastSavedTime {#getLastSavedTime}

| Name | Description |
| --- | --- |
| getLastSavedTime () | 返回演示文稿最后一次修改的日期。值为 UTC。只读（在 Presentation.DocumentProperties 中因为在 IPresentation 对象保存过程中会内部更新）。可通过 IPresentationInfo#readDocumentProperties 返回的 DocumentProperties 实例进行修改。请参阅 IPresentationInfo#updateDocumentProperties(IDocumentProperties) 方法摘要中的示例。 |

**返回：**  
Date

---

### getLinksUpToDate {#getLinksUpToDate}

| Name | Description |
| --- | --- |
| getLinksUpToDate () | 指示文档中的超链接是否是最新的。将此元素设为 true 表示超链接已更新。将此元素设为 false 表示超链接已过期。可读写 boolean。 |

**返回：**  
boolean

---

### getManager {#getManager}

| Name | Description |
| --- | --- |
| getManager () | 返回或设置管理者属性。可读写 String。 |

**返回：**  
String

---

### getMultimediaClips {#getMultimediaClips}

| Name | Description |
| --- | --- |
| getMultimediaClips () | 返回文档中存在的声音或视频剪辑的总数。只读 int。 |

**返回：**  
int

---

### getNameOfApplication {#getNameOfApplication}

| Name | Description |
| --- | --- |
| getNameOfApplication () | 返回或设置应用程序的名称。可读写 String。 |

**返回：**  
String

---

### getNotes {#getNotes}

| Name | Description |
| --- | --- |
| getNotes () | 返回包含备注的演示文稿幻灯片数量。只读 int。 |

**返回：**  
int

---

### getParagraphs {#getParagraphs}

| Name | Description |
| --- | --- |
| getParagraphs () | 返回文档中找到的段落总数（如适用）。只读 int。 |

**返回：**  
int

---

### getPresentationFormat {#getPresentationFormat}

| Name | Description |
| --- | --- |
| getPresentationFormat () | 返回或设置演示文稿的预期格式。可读写 String。 |

**返回：**  
String

---

### getRevisionNumber {#getRevisionNumber}

| Name | Description |
| --- | --- |
| getRevisionNumber () | 返回或设置演示文稿的修订号。可读写 int。 |

**返回：**  
int

---

### getScaleCrop {#getScaleCrop}

| Name | Description |
| --- | --- |
| getScaleCrop () | 指示文档缩略图的显示模式。将此元素设为 true 以启用缩放文档缩略图以适配显示。将此元素设为 false 以启用裁剪文档缩略图仅显示适合显示的部分。可读写 boolean。 |

**返回：**  
boolean

---

### getSensitivityLabels {#getSensitivityLabels}

| Name | Description |
| --- | --- |
| getSensitivityLabels () | 从自定义文档属性（Microsoft Information Protection SDK 元数据）获取敏感度标签数组。 |

**返回：**  
[SensitivityLabel](../sensitivitylabel)

---

### getSharedDoc {#getSharedDoc}

| Name | Description |
| --- | --- |
| getSharedDoc () | 确定演示文稿是否在多个人之间共享。可读写 boolean。 |

**返回：**  
boolean

---

### getSlides {#getSlides}

| Name | Description |
| --- | --- |
| getSlides () | 返回演示文稿文档中幻灯片的总数。只读 int。 |

**返回：**  
int

---

### getSubject {#getSubject}

| Name | Description |
| --- | --- |
| getSubject () | 返回或设置演示文稿的主题。可读写 String。 |

**返回：**  
String

---

### getTitle {#getTitle}

| Name | Description |
| --- | --- |
| getTitle () | 返回或设置演示文稿的标题。可读写 String。 |

**返回：**  
String

---

### getTitlesOfParts {#getTitlesOfParts}

| Name | Description |
| --- | --- |
| getTitlesOfParts () | 指定每个文档部分的标题。这些部分不是文档部分，而是文档章节的概念表示。只读 String[]. |

**返回：**  
String

---

### getTotalEditingTime {#getTotalEditingTime}

| Name | Description |
| --- | --- |
| getTotalEditingTime () | 演示文稿的总编辑时间。读/写 double. |

**返回：**
double


---


### getWords {#getWords}

| Name | Description |
| --- | --- |
| getWords () | 返回文档中包含的单词总数。只读 int. |

**返回：**
int


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (String) | 返回或设置与指定名称关联的自定义属性。读/写 Object。值可以是 int、float、String、boolean 或 Date. |

**返回：**
Object


---


### removeCustomProperty {#removeCustomProperty}

| Name | Description |
| --- | --- |
| removeCustomProperty (String) | 删除与指定名称关联的自定义属性。 |

**参数：**

| Name | Type | Description |
| --- | --- | --- |
| name | String | 要删除的自定义属性的名称. |

**返回：**
boolean


---


### setApplicationTemplate {#setApplicationTemplate}

| Name | Description |
| --- | --- |
| setApplicationTemplate (String) | 返回或设置应用程序的模板。读/写 String. |

**返回：**
void


---


### setAuthor {#setAuthor}

| Name | Description |
| --- | --- |
| setAuthor (String) | 返回或设置演示文稿的作者。读/写 String. |

**返回：**
void


---


### setCategory {#setCategory}

| Name | Description |
| --- | --- |
| setCategory (String) | 返回或设置演示文稿的类别。读/写 String. |

**返回：**
void


---


### setComments {#setComments}

| Name | Description |
| --- | --- |
| setComments (String) | 返回或设置演示文稿的注释。读/写 String. |

**返回：**
void


---


### setCompany {#setCompany}

| Name | Description |
| --- | --- |
| setCompany (String) | 返回或设置公司属性。读/写 String. |

**返回：**
void


---


### setContentStatus {#setContentStatus}

| Name | Description |
| --- | --- |
| setContentStatus (String) | 返回或设置演示文稿的内容状态。读/写 String. |

**返回：**
void


---


### setContentType {#setContentType}

| Name | Description |
| --- | --- |
| setContentType (String) | 返回或设置演示文稿的内容类型。读/写 String. |

**返回：**
void


---


### setCreatedTime {#setCreatedTime}

| Name | Description |
| --- | --- |
| setCreatedTime (Date) | 返回演示文稿的创建日期。值为 UTC 时间。读/写 java.util.Date. |

**返回：**
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, boolean) | 设置具有指定名称的布尔自定义属性。 |

**参数：**

| Name | Type | Description |
| --- | --- | --- |
| name | String | 要设置的自定义属性的名称 |
| value | boolean | 自定义属性值 |

**返回：**
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, int) | 设置具有指定名称的整数自定义属性。 |

**参数：**

| Name | Type | Description |
| --- | --- | --- |
| name | String | 要设置的自定义属性的名称 |
| value | int | 自定义属性值 |

**返回：**
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, Date) | 设置具有指定名称的 DateTime 自定义属性。 |

**参数：**

| Name | Type | Description |
| --- | --- | --- |
| name | String | 要设置的自定义属性的名称 |
| value | Date | 自定义属性值 |

**返回：**
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, String) | 设置具有指定名称的字符串自定义属性。 |

**参数：**

| Name | Type | Description |
| --- | --- | --- |
| name | String | 要设置的自定义属性的名称 |
| value | String | 自定义属性值 |

**返回：**
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, float) | 设置具有指定名称的浮点自定义属性。 |

**参数：**

| Name | Type | Description |
| --- | --- | --- |
| name | String | 要设置的自定义属性的名称 |
| value | float | 自定义属性值 |

**返回：**
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, double) | 设置具有指定名称的 double 自定义属性。 |

**参数：**

| Name | Type | Description |
| --- | --- | --- |
| name | String | 要设置的自定义属性的名称 |
| value | double | 自定义属性值 |

**返回：**
void


---


### setHyperlinkBase {#setHyperlinkBase}

| Name | Description |
| --- | --- |
| setHyperlinkBase (String) | 返回或设置 HyperlinkBase 文档属性。读/写 String. |

**返回：**
void


---


### setHyperlinksChanged {#setHyperlinksChanged}

| Name | Description |
| --- | --- |
| setHyperlinksChanged (boolean) | 指定此部分中的一个或多个超链接已由生成器专门在此部分更新。下一个打开此文档的生成器应使用此部分中指定的新超链接更新超链接关系。读/写 boolean. |

**返回：**
void


---


### setKeywords {#setKeywords}

| Name | Description |
| --- | --- |
| setKeywords (String) | 返回或设置演示文稿的关键字。读/写 String. |

**返回：**
void


---


### setLastPrinted {#setLastPrinted}

| Name | Description |
| --- | --- |
| setLastPrinted (Date) | 返回演示文稿上次打印的日期。读/写 java.util.Date. |

**返回：**
void


---


### setLastSavedBy {#setLastSavedBy}

| Name | Description |
| --- | --- |
| setLastSavedBy (String) | 返回或设置最后一次修改演示文稿的人的姓名。读/写 String. |

**返回：**
void


---


### setLastSavedTime {#setLastSavedTime}

| Name | Description |
| --- | --- |
| setLastSavedTime (Date) | 返回演示文稿最后修改的日期。值为 UTC 时间。在 Presentation.DocumentProperties 情况下为只读（因为在 IPresentation 对象保存过程中会内部更新）。可以通过方法 IPresentationInfo#readDocumentProperties 返回的 DocumentProperties 实例进行更改。请参阅 IPresentationInfo#updateDocumentProperties(IDocumentProperties) 方法摘要中的示例。 |

**返回：**
void


---


### setLinksUpToDate {#setLinksUpToDate}

| Name | Description |
| --- | --- |
| setLinksUpToDate (boolean) | 指示文档中的超链接是否是最新的。将此元素设为 true 表示超链接已更新。将此元素设为 false 表示超链接已过时。读/写 boolean. |

**返回：**
void


---


### setManager {#setManager}

| Name | Description |
| --- | --- |
| setManager (String) | 返回或设置经理属性。读/写 String. |

**返回：**
void


---


### setNameOfApplication {#setNameOfApplication}

| Name | Description |
| --- | --- |
| setNameOfApplication (String) | 返回或设置应用程序的名称。读/写 String. |

**返回：**
void


---


### setPresentationFormat {#setPresentationFormat}

| Name | Description |
| --- | --- |
| setPresentationFormat (String) | 返回或设置演示文稿的预期格式。读/写 String. |

**返回：**
void


---


### setRevisionNumber {#setRevisionNumber}

| Name | Description |
| --- | --- |
| setRevisionNumber (int) | 返回或设置演示文稿的修订号。读/写 int. |

**返回：**
void


---


### setScaleCrop {#setScaleCrop}

| Name | Description |
| --- | --- |
| setScaleCrop (boolean) | 指示文档缩略图的显示模式。将此元素设为 true 以启用将文档缩略图缩放至显示区域。将此元素设为 false 以启用裁剪文档缩略图，仅显示适合显示区域的部分。读/写 boolean. |

**返回：**
void


---


### setSharedDoc {#setSharedDoc}

| Name | Description |
| --- | --- |
| setSharedDoc (boolean) | 确定演示文稿是否在多个人之间共享。读/写 boolean. |

**返回：**
void


---


### setSubject {#setSubject}

| Name | Description |
| --- | --- |
| setSubject (String) | 返回或设置演示文稿的主题。读/写 String. |

**返回：**
void


---


### setTitle {#setTitle}

| Name | Description |
| --- | --- |
| setTitle (String) | 返回或设置演示文稿的标题。读/写 String. |

**返回：**
void


---


### setTotalEditingTime {#setTotalEditingTime}

| Name | Description |
| --- | --- |
| setTotalEditingTime (double) | 演示文稿的总编辑时间。读/写 double. |

**返回：**
void


---


### set_Item {#set_Item}

| Name | Description |
| --- | --- |
| set_Item (String, Object) | 返回或设置与指定名称关联的自定义属性。读/写 Object。值可以是 int、float、String、boolean 或 Date. |

**返回：**
void


---