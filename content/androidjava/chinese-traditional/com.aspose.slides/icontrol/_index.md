---
title: IControl
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 ActiveX 控制項。
type: docs
url: /zh-hant/com.aspose.slides/icontrol/
---
**所有已實作的介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

表示 ActiveX 控制項。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | Returns the name of this control. |
| [setName(String value)](#setName-java.lang.String-) | Returns the name of this control. |
| [getClassId()](#getClassId--) | Gets class id of this control. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returns ControlEx image fill properties object. |
| [getFrame()](#getFrame--) | Returns or sets control's frame. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returns or sets control's frame. |
| [getProperties()](#getProperties--) | Returns a collection of ActiveX properties. |
| [getPersistence()](#getPersistence--) | Gets the method used to store properties of the ActiveX control. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

返回此控制項的名稱。可讀寫 String。

**返回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

返回此控制項的名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

取得此控制項的類別 ID。唯讀 java.util.UUID。

**返回：**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

返回 ControlEx 影像填充屬性物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

返回或設定控制項的框架。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**返回：**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

返回或設定控制項的框架。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

返回 ActiveX 屬性的集合。唯讀 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)。

**返回：**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

取得用於儲存 ActiveX 控制項屬性的方式。唯讀 [PersistenceType](../../com.aspose.slides/persistencetype)。

**返回：**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

指定當持久化方法為 PersistStream、PersistStreamInit 或 PersistStorage 時，ActiveX 控制項的持久化方式。

**返回：**
byte[]