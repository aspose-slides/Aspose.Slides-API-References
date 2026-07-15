---
title: IOleObjectFrame
second_title: Aspose.Slides for Android via Java API 參考
description: 表示投影片上的 OLE 物件。
type: docs
url: /zh-hant/com.aspose.slides/ioleobjectframe/
---
**已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

表示投影片上的 OLE 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 返回 OleObject 圖像填充屬性物件。 |
| [getObjectName()](#getObjectName--) | 返回或設定物件的名稱。 |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | 返回或設定物件的名稱。 |
| [getEmbeddedData()](#getEmbeddedData--) | 取得 OLE 嵌入資料的資訊。 |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | 設定 OLE 嵌入資料的資訊。 |
| [getObjectProgId()](#getObjectProgId--) | 返回物件的 ProgID。 |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | 返回物件的 ProgID。 |
| [getLinkFileName()](#getLinkFileName--) | 返回已連結檔案的完整路徑。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回已連結檔案的完整路徑。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回已連結檔案的完整路徑。 |
| [getLinkPathRelative()](#getLinkPathRelative--) | 若存在，返回已連結檔案的相對路徑；否則返回空字串。 |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | 返回嵌入 OLE 物件的檔名 |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | 返回嵌入 OLE 物件的路徑 |
| [isObjectIcon()](#isObjectIcon--) | 判斷物件是否以圖示方式顯示。 |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | 判斷物件是否以圖示方式顯示。 |
| [isObjectLink()](#isObjectLink--) | 判斷物件是否已連結至外部檔案。 |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | 判斷已連結的嵌入物件在開啟或列印簡報時是否自動更新。 |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | 判斷已連結的嵌入物件在開啟或列印簡報時是否自動更新。 |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | 返回或設定 OleObject 圖示的標題。 |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | 返回或設定 OleObject 圖示的標題。 |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

返回 OleObject 圖像填充屬性物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

返回或設定物件的名稱。可讀寫 String。

**返回：**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

返回或設定物件的名稱。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

取得 OLE 嵌入資料的資訊。唯讀 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)。

**返回：**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

設定 OLE 嵌入資料的資訊。

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入資料 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

此方法會變更物件屬性以符合新資料，並將 IsObjectLink 旗標設為 false，表示 OLE 物件為嵌入式。 |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

返回物件的 ProgID。唯讀 String。

**返回：**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

返回物件的 ProgID。唯讀 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

返回已連結檔案的完整路徑。將使用短檔名。唯讀 String。

**返回：**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

返回已連結檔案的完整路徑。將使用長檔名。可讀寫 String。

**返回：**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

返回已連結檔案的完整路徑。將使用長檔名。可讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

若存在，返回已連結檔案的相對路徑；否則返回空字串。唯讀 String。

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


在 PowerPoint 簡報中，某些 Ole 物件連結可能以相對表示方式存在。

**返回：**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

返回嵌入 OLE 物件的檔名

**返回：**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

返回嵌入 OLE 物件的路徑

**返回：**
java.lang.String

### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

判斷物件是否以圖示方式顯示。可讀寫 boolean。

**返回：**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

判斷物件是否以圖示方式顯示。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

判斷物件是否已連結至外部檔案。唯讀 boolean。

**返回：**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

判斷已連結的嵌入物件在開啟或列印簡報時是否自動更新。可讀寫 boolean。

**返回：**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

判斷已連結的嵌入物件在開啟或列印簡報時是否自動更新。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

返回或設定 OleObject 圖示的標題。可讀寫 String。

--------------------

當 IsObjectIcon == false 時，此值會被忽略。字串會依 OLE 圖示大小截斷。

**返回：**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

返回或設定 OleObject 圖示的標題。可讀寫 String。

--------------------

當 IsObjectIcon == false 時，此值會被忽略。字串會依 OLE 圖示大小截斷。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |