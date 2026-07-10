---
title: IControl
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示一个 ActiveX 控件。
type: docs
url: /zh/com.aspose.slides/icontrol/
---
**已实现的接口:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

表示一个 ActiveX 控件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 返回此控件的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 返回此控件的名称。 |
| [getClassId()](#getClassId--) | 获取此控件的类标识符。 |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 返回 ControlEx 图像填充属性对象。 |
| [getFrame()](#getFrame--) | 返回或设置控件的框架。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 返回或设置控件的框架。 |
| [getProperties()](#getProperties--) | 返回 ActiveX 属性的集合。 |
| [getPersistence()](#getPersistence--) | 获取用于存储 ActiveX 控件属性的方法。 |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | 指定 ActiveX 控件的持久性，当持久化使用的方法为 PersistStream、PersistStreamInit 或 PersistStorage 时。 |

### getName() {#getName--}
```
public abstract String getName()
```

返回此控件的名称。可读写 String.

**返回：**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回此控件的名称。可读写 String.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

获取此控件的类标识符。只读 java.util.UUID.

**返回：**
java.util.UUID

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

返回 ControlEx 图像填充属性对象。只读 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**返回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

返回或设置控件的框架。可读写 [IShapeFrame](../../com.aspose.slides/ishapeframe).

**返回：**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

返回或设置控件的框架。可读写 [IShapeFrame](../../com.aspose.slides/ishapeframe).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

返回 ActiveX 属性的集合。只读 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**返回：**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

获取用于存储 ActiveX 控件属性的方法。只读 [PersistenceType](../../com.aspose.slides/persistencetype).

**返回：**
int

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

指定 ActiveX 控件的持久性，当持久化使用的方法为 PersistStream、PersistStreamInit 或 PersistStorage 时。

**返回：**
byte[]