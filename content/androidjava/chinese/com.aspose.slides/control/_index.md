---
title: Control
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个 ActiveX 控件。
type: docs
url: /zh/com.aspose.slides/control/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

表示一个 ActiveX 控件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPersistence()](#getPersistence--) | 获取用于存储 ActiveX 控件属性的方法。 |
| [getName()](#getName--) | 获取或设置此控件的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置此控件的名称。 |
| [getClassId()](#getClassId--) | 获取此控件的类标识。 |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | 获取此控件的类标识。 |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 返回 Control image fill properties 对象。 |
| [getFrame()](#getFrame--) | 获取或设置控件的框架。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 获取或设置控件的框架。 |
| [getProperties()](#getProperties--) | 返回 ActiveX 属性的集合。 |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | 指定在使用 PersistStream、PersistStreamInit 或 PersistStorage 进行持久化时 ActiveX 控件的持久化方式。 |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

获取用于存储 ActiveX 控件属性的方法。 只读 [PersistenceType](../../com.aspose.slides/persistencetype)。

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //使用您自己的方法来管理存储在其二进制文件中的 ActiveX 属性
>  }
>  ```

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```

Gets or sets the name of this control. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Gets or sets the name of this control. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Gets class id of this control. Read-only java.util.UUID.

**Returns:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

获取此控件的类标识。只读 java.util.UUID.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Returns Control image fill properties object. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Returns or sets control's frame. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Returns or sets control's frame. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Returns a collection of ActiveX properties. Read-only [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Note: Aspose.Slides supports only XML based ActiveX properties. If properties stored in binary format, this property will return null.

**Returns:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```
Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //使用您自己的方法来管理存储在其二进制文件中的 ActiveX 属性
>  }
> ```

**Returns:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the base slide. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()


返回演示文稿。 只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)