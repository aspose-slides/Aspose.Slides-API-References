---
title: Control
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/control/
---
## Control 类

表示一个 ActiveX 控件。

### getActiveXControlBinary {#getActiveXControlBinary}

| 名称 | 描述 |
| --- | --- |
| getActiveXControlBinary () | 指定在持久化方法为 PersistStream、PersistStreamInit 或 PersistStorage 时 ActiveX 控件的持久性。 |

**返回：**
byte


---


### getClassId {#getClassId}

| 名称 | 描述 |
| --- | --- |
| getClassId () | 获取此控件的类标识。只读 java.util.UUID。 |

**返回：**
UUID


---


### getFrame {#getFrame}

| 名称 | 描述 |
| --- | --- |
| getFrame () | 返回或设置控件的框架。读写 IShapeFrame。 |

**返回：**
[ShapeFrame](../shapeframe)


---


### getName {#getName}

| 名称 | 描述 |
| --- | --- |
| getName () | 获取或设置此控件的名称。读写 String。 |

**返回：**
String


---


### getPersistence {#getPersistence}

| 名称 | 描述 |
| --- | --- |
| getPersistence () | 获取用于存储 ActiveX 控件属性的方法。只读 PersistenceType。 |

**返回：**
int


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () |  |

**返回：**
[Presentation](../presentation)


---


### getProperties {#getProperties}

| 名称 | 描述 |
| --- | --- |
| getProperties () | 返回 ActiveX 属性的集合。只读 IControlPropertiesCollection。注意：Aspose.Slides 仅支持基于 XML 的 ActiveX 属性。如果属性以二进制格式存储，此属性将返回 null。 |

**返回：**
[ControlPropertiesCollection](../controlpropertiescollection)


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () |  |

**返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSubstitutePictureFormat {#getSubstitutePictureFormat}

| 名称 | 描述 |
| --- | --- |
| getSubstitutePictureFormat () | 返回控件图像填充属性对象。只读 IPictureFillFormat。 |

**返回：**
[PictureFillFormat](../picturefillformat)


---


### setClassId {#setClassId}

| 名称 | 描述 |
| --- | --- |
| setClassId (UUID) | 获取此控件的类标识。只读 java.util.UUID。 |

**返回：**
void


---


### setFrame {#setFrame}

| 名称 | 描述 |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | 返回或设置控件的框架。读写 IShapeFrame。 |

**返回：**
void


---


### setName {#setName}

| 名称 | 描述 |
| --- | --- |
| setName (String) | 获取或设置此控件的名称。读写 String。 |

**返回：**
void


---