---
title: Control
second_title: Aspose.Slides for Android 的 Java API 參考
description: 代表一個 ActiveX 控制項。
type: docs
url: /zh-hant/com.aspose.slides/control/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**
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
| [getClassId()](#getClassId--) | 取得此控制項的類別 ID。 |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | 取得此控制項的類別 ID。 |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 傳回控制項圖像填充屬性物件。 |
| [getFrame()](#getFrame--) | 傳回或設定控制項的框架。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 傳回或設定控制項的框架。 |
| [getProperties()](#getProperties--) | 傳回 ActiveX 屬性的集合。 |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | 指定在使用 PersistStream、PersistStreamInit 或 PersistStorage 方式持久化時 ActiveX 控制項的持久化行為。 |
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
>      YourMethodHere(control.getActiveXControlBinary()); //使用您自己的方法來管理以二進位檔案儲存的 ActiveX 屬性
>  }
> ```

**傳回值:**
int

### getName() {#getName--}
```
public final String getName()
```

取得或設定此控制項的名稱。讀寫 String。

**傳回值:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

取得或設定此控制項的名稱。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

取得此控制項的類別 ID。唯讀 java.util.UUID。

**傳回值:**
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

取得此控制項的類別 ID。唯讀 java.util.UUID。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

傳回控制項圖像填充屬性物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**傳回值:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

傳回或設定控制項的框架。讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**傳回值:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

傳回或設定控制項的框架。讀寫 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

傳回 ActiveX 屬性的集合。唯讀 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)。

--------------------

**注意:** Aspose.Slides 僅支援基於 XML 的 ActiveX 屬性。如果屬性以二進位格式儲存，則此屬性將傳回 null。

**傳回值:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

指定在使用 PersistStream、PersistStreamInit 或 PersistStorage 方式持久化時 ActiveX 控制項的持久化行為。

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
>      YourMethodHere(control.getActiveXControlBinary()); //使用您自己的方法來管理儲存在二進位檔案中的 ActiveX 屬性
>  }
> ```


**傳回值:**
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回基礎投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**傳回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回值:**
[IPresentation](../../com.aspose.slides/ipresentation)