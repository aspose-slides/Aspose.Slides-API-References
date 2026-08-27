---
title: PortionFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/portionformat/
---
## PortionFormat 类

 此类包含文本片段格式属性。与 IPortionFormatEffectiveData 不同，此类的所有属性均可写。  
 此类用于返回和操作为特定片段定义的文本片段格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您会得到“未定义”的值。  
 若要获取包括继承在内的有效格式参数值，需要使用 PortionFormat#getEffective 方法，该方法返回一个 IPortionFormatEffectiveData 实例。

### PortionFormat {#PortionFormat}

| 名称 | 描述 |
| --- | --- |
| PortionFormat() | 初始化 PortionFormat 类的新实例。 |

 **返回：**
PortionFormat


---


### getBookmarkId {#getBookmarkId}

| 名称 | 描述 |
| --- | --- |
| getBookmarkId () | 返回或设置书签标识符。读写 String。 |

 **返回：**
String


---


### getEffective {#getEffective}

| 名称 | 描述 |
| --- | --- |
| getEffective () | 获取已应用继承的有效片段格式数据。 |

 **返回：**
PortionFormatEffectiveData


---


### getHyperlinkClick {#getHyperlinkClick}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkClick () | 返回或设置鼠标点击时定义的超链接。读写 IHyperlink。 |

 **返回：**
[Hyperlink](../hyperlink)


---


### getHyperlinkManager {#getHyperlinkManager}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkManager () | 超链接管理器。只读 IHyperlinkManager。 |

 **返回：**
[HyperlinkManager](../hyperlinkmanager)


---


### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkMouseOver () | 返回或设置鼠标悬停时定义的超链接。读写 IHyperlink。 |

 **返回：**
[Hyperlink](../hyperlink)


---


### getSmartTagClean {#getSmartTagClean}

| 名称 | 描述 |
| --- | --- |
| getSmartTagClean () | 确定是否应清除智能标签。未应用继承。读写 boolean。 |

 **返回：**
boolean


---


### setBookmarkId {#setBookmarkId}

| 名称 | 描述 |
| --- | --- |
| setBookmarkId (String) | 返回或设置书签标识符。读写 String。 |

 **返回：**
void


---


### setHyperlinkClick {#setHyperlinkClick}

| 名称 | 描述 |
| --- | --- |
| setHyperlinkClick ([Hyperlink](../hyperlink)) | 返回或设置鼠标点击时定义的超链接。读写 IHyperlink。 |

 **返回：**
void


---


### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| 名称 | 描述 |
| --- | --- |
| setHyperlinkMouseOver ([Hyperlink](../hyperlink)) | 返回或设置鼠标悬停时定义的超链接。读写 IHyperlink。 |

 **返回：**
void


---


### setSmartTagClean {#setSmartTagClean}

| 名称 | 描述 |
| --- | --- |
| setSmartTagClean (boolean) | 确定是否应清除智能标签。未应用继承。读写 boolean。 |

 **返回：**
void


---