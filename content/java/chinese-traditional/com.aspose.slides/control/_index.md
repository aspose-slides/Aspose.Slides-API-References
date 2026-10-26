---
title: Control
second_title: Aspose.Slides for Java API 參考
description: 表示一個 ActiveX 控制項。
type: docs
url: /zh-hant/com.aspose.slides/control/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面：**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

表示一個 ActiveX 控制項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPersistence()](#getPersistence--) | 取得用於儲存 ActiveX 控制項屬性的方式。 |
| [getName()](#getName--) | 取得或設定此控制項的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 取得或設定此控制項的名稱。 |
| [getClassId()](#getClassId--) | 取得此控制項的 class id。 |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | 取得此控制項的 class id。 |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 傳回 Control 影像填充屬性物件。 |
| [getFrame()](#getFrame--) | 傳回或設定 control 的框架。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 傳回或設定 control 的框架。 |
| [getProperties()](#getProperties--) | 傳回 ActiveX 屬性的集合。 |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | 指定 ActiveX 控制項的持續性，當使用的持續化方法為 PersistStream、PersistStreamInit 或 PersistStorage 時。 |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```


取得用於儲存 ActiveX 控制項屬性的方式。唯讀 [PersistenceType](../../com.aspose.slides/persistencetype)。

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
>      YourMethodHere(control.getActiveXControlBinary()); //Use your own method for managing ActiveX properties stored in its binary file
>  }
> ```

**傳回：**
int
### getName() {#getName--}
```
public final String getName()
```


取得或設定此控制項的名稱。可讀寫 String。

**傳回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


取得或設定此控制項的名稱。可讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```


取得此控制項的 class id。唯讀 java.util.UUID。

**傳回：**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```


取得此控制項的 class id。唯讀 java.util.UUID。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


傳回 Control 影像填充屬性物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**傳回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


傳回或設定 control 的框架。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**傳回：**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


傳回或設定 control 的框架。可讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```


傳回 ActiveX 屬性的集合。唯讀 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)。

--------------------

注意：Aspose.Slides 僅支援基於 XML 的 ActiveX 屬性。如果屬性以二進位格式儲存，則此屬性將傳回 null。

**傳回：**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```


指定 ActiveX 控制項的持續性，當使用的持續化方法為 PersistStream、PersistStreamInit 或 PersistStorage 時。

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
>      YourMethodHere(control.getActiveXControlBinary()); //使用您自己的方法來管理存儲於其二進位檔案中的 ActiveX 屬性
>  }
> ```


**傳回：**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


傳回基底投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**傳回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


傳回簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回：**
[IPresentation](../../com.aspose.slides/ipresentation)