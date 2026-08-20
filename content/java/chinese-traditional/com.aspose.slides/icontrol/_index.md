---
title: IControl
second_title: Aspose.Slides for Java API 參考文件
description: 代表 ActiveX 控制項。
type: docs
url: /zh-hant/com.aspose.slides/icontrol/
---
**所有已實作的介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

代表 ActiveX 控制項。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 傳回此控制項的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 傳回此控制項的名稱。 |
| [getClassId()](#getClassId--) | 取得此控制項的類別 ID。 |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 傳回 ControlEx 圖像填充屬性物件。 |
| [getFrame()](#getFrame--) | 傳回或設定控制項的框架。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 傳回或設定控制項的框架。 |
| [getProperties()](#getProperties--) | 傳回 ActiveX 屬性集合。 |
| [getPersistence()](#getPersistence--) | 取得用於儲存 ActiveX 控制項屬性的方式。 |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | 指定在持久化方法為 PersistStream、PersistStreamInit 或 PersistStorage 時，ActiveX 控制項的持久化方式。 |
### getName() {#getName--}
```
public abstract String getName()
```

傳回此控制項的名稱。讀/寫 String.

**傳回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

傳回此控制項的名稱。讀/寫 String.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

取得此控制項的類別 ID。唯讀 java.util.UUID。

**傳回：**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

傳回 ControlEx 圖像填充屬性物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**傳回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

傳回或設定控制項的框架。讀/寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**傳回：**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

傳回或設定控制項的框架。讀/寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

傳回 ActiveX 屬性集合。唯讀 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)。

**傳回：**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

取得用於儲存 ActiveX 控制項屬性的方式。唯讀 [PersistenceType](../../com.aspose.slides/persistencetype)。

**傳回：**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

指定在持久化方法為 PersistStream、PersistStreamInit 或 PersistStorage 時，ActiveX 控制項的持久化方式。

**傳回：**
byte[]