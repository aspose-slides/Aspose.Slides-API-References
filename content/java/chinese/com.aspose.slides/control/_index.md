---
title: Control
second_title: Aspose.Slides for Java API 参考
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

表示一个ActiveX控件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPersistence()](#getPersistence--) | 获取用于存储ActiveX控件属性的方法。 |
| [getName()](#getName--) | 获取或设置此控件的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置此控件的名称。 |
| [getClassId()](#getClassId--) | 获取此控件的类标识。 |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | 获取此控件的类标识。 |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 返回控制图像填充属性对象。 |
| [getFrame()](#getFrame--) | 返回或设置控件的框架。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 返回或设置控件的框架。 |
| [getProperties()](#getProperties--) | 返回ActiveX属性的集合。 |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | 指定ActiveX控件的持久性，当用于持久化的方法是PersistStream、PersistStreamInit或PersistStorage时。 |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

获取用于存储ActiveX控件属性的方法。只读 [PersistenceType](../../com.aspose.slides/persistencetype)。

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
> ```


**返回:**  
int

### getName() {#getName--}
```
public final String getName()
```

获取或设置此控件的名称。读/写 String。

**返回:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

获取或设置此控件的名称。读/写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

获取此控件的类标识。只读 java.util.UUID。

**返回:**  
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

获取此控件的类标识。只读 java.util.UUID。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

返回控制图像填充属性对象。只读 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

返回或设置控件的框架。读/写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**返回:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

返回或设置控件的框架。读/写 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

返回ActiveX属性的集合。只读 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)。

--------------------

注意：Aspose.Slides 仅支持基于 XML 的 ActiveX 属性。如果属性以二进制格式存储，此属性将返回 null。

**返回:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

指定ActiveX控件的持久性，当用于持久化的方法是PersistStream、PersistStreamInit或PersistStorage时。

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


**返回:**  
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回基础幻灯片。只读 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**  
[IPresentation](../../com.aspose.slides/ipresentation)