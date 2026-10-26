---
title: OleObjectFrame
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/oleobjectframe/
---
## OleObjectFrame 类

表示幻灯片上的 OLE 对象。

### getEmbeddedData {#getEmbeddedData}

| 名称 | 描述 |
| --- | --- |
| getEmbeddedData () | 获取或设置 OLE 嵌入数据的信息。读/写 IOleEmbeddedDataInfo。 |

**返回:**
[OleEmbeddedDataInfo](../oleembeddeddatainfo)

---


### getEmbeddedFileLabel {#getEmbeddedFileLabel}

| 名称 | 描述 |
| --- | --- |
| getEmbeddedFileLabel () | 返回嵌入 OLE 对象的文件名 |

**返回:**
String

---


### getEmbeddedFileName {#getEmbeddedFileName}

| 名称 | 描述 |
| --- | --- |
| getEmbeddedFileName () | 返回嵌入 OLE 对象的路径 |

**返回:**
String

---


### getLinkFileName {#getLinkFileName}

| 名称 | 描述 |
| --- | --- |
| getLinkFileName () | 返回链接文件的完整路径。将使用短文件名。只读 String。 |

**返回:**
String

---


### getLinkPathLong {#getLinkPathLong}

| 名称 | 描述 |
| --- | --- |
| getLinkPathLong () | 返回链接文件的完整路径。将使用长文件名。读/写 String。 |

**返回:**
String

---


### getLinkPathRelative {#getLinkPathRelative}

| 名称 | 描述 |
| --- | --- |
| getLinkPathRelative () | 如果存在，则返回链接文件的相对路径；否则返回空字符串。只读 String。在 Ppt 演示文稿中，某些 Ole 对象链接可能采用相对表示。 |

**返回:**
String

---


### getObjectName {#getObjectName}

| 名称 | 描述 |
| --- | --- |
| getObjectName () | 获取或设置对象的名称。读/写 String。 |

**返回:**
String

---


### getObjectProgId {#getObjectProgId}

| 名称 | 描述 |
| --- | --- |
| getObjectProgId () | 返回对象的 ProgID。只读 String。 |

**返回:**
String

---


### getSubstitutePictureFormat {#getSubstitutePictureFormat}

| 名称 | 描述 |
| --- | --- |
| getSubstitutePictureFormat () | 返回 OleObject 图像填充属性对象。只读 IPictureFillFormat。 |

**返回:**
[PictureFillFormat](../picturefillformat)

---


### getSubstitutePictureTitle {#getSubstitutePictureTitle}

| 名称 | 描述 |
| --- | --- |
| getSubstitutePictureTitle () | 获取或设置 OleObject 图标的标题。读/写 String。当 IsObjectIcon == false 时此值被忽略。字符串可能会根据 Ole 图标的大小被截断。 |

**返回:**
String

---


### getUpdateAutomatic {#getUpdateAutomatic}

| 名称 | 描述 |
| --- | --- |
| getUpdateAutomatic () | 确定在打开或打印演示文稿时是否自动更新链接的嵌入对象。读/写 boolean。 |

**返回:**
boolean

---


### isObjectIcon {#isObjectIcon}

| 名称 | 描述 |
| --- | --- |
| isObjectIcon () | 确定对象是否以图标形式可见。读/写 boolean。 |

**返回:**
boolean

---


### isObjectLink {#isObjectLink}

| 名称 | 描述 |
| --- | --- |
| isObjectLink () | 确定对象是否链接到外部文件。只读 boolean。 |

**返回:**
boolean

---


### setEmbeddedData {#setEmbeddedData}

| 名称 | 描述 |
| --- | --- |
| setEmbeddedData ([OleEmbeddedDataInfo](../oleembeddeddatainfo)) | 设置 OLE 嵌入数据的信息。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| embeddedData | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | 嵌入数据 IOleEmbeddedDataInfo 此方法更改对象的属性以反映新数据，并将 IsObjectLink 标志设置为 false，表示 OLE 对象为嵌入的。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentNullException | 当 embeddedData 参数为 null 时。 |

---


### setLinkPathLong {#setLinkPathLong}

| 名称 | 描述 |
| --- | --- |
| setLinkPathLong (String) | 返回链接文件的完整路径。将使用长文件名。读/写 String。 |

**返回:**
void

---


### setObjectIcon {#setObjectIcon}

| 名称 | 描述 |
| --- | --- |
| setObjectIcon (boolean) | 确定对象是否以图标形式可见。读/写 boolean。 |

**返回:**
void

---


### setObjectName {#setObjectName}

| 名称 | 描述 |
| --- | --- |
| setObjectName (String) | 获取或设置对象的名称。读/写 String。 |

**返回:**
void

---


### setObjectProgId {#setObjectProgId}

| 名称 | 描述 |
| --- | --- |
| setObjectProgId (String) | 返回对象的 ProgID。只读 String。 |

**返回:**
void

---


### setSubstitutePictureTitle {#setSubstitutePictureTitle}

| 名称 | 描述 |
| --- | --- |
| setSubstitutePictureTitle (String) | 获取或设置 OleObject 图标的标题。读/写 String。当 IsObjectIcon == false 时此值被忽略。字符串可能会根据 Ole 图标的大小被截断。 |

**返回:**
void

---


### setUpdateAutomatic {#setUpdateAutomatic}

| 名称 | 描述 |
| --- | --- |
| setUpdateAutomatic (boolean) | 确定在打开或打印演示文稿时是否自动更新链接的嵌入对象。读/写 boolean。 |

**返回:**
void

---