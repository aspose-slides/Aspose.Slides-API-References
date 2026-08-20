---
title: OleObjectFrame
second_title: Aspose.Slides for Java API 參考文件
description: 表示投影片上的 OLE 物件。
type: docs
url: /zh-hant/com.aspose.slides/oleobjectframe/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有實作的介面：**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

表示投影片上的 OLE 物件。

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // 載入 PPTX 到簡報物件
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // 取得第一張投影片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 將形狀轉型為 OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // 讀取 OLE 物件並寫入磁碟
>      if (oleObjectFrame != null) {
>          // 取得嵌入檔案資料
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // 取得嵌入檔案副檔名
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // 建立儲存抽取檔案的路徑
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // 儲存抽取的資料
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 返回 OleObject 影像填充屬性物件。 |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | 返回或設定 OleObject 圖示的標題。 |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | 返回或設定 OleObject 圖示的標題。 |
| [getObjectName()](#getObjectName--) | 返回或設定物件的名稱。 |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | 返回或設定物件的名稱。 |
| [getObjectProgId()](#getObjectProgId--) | 返回物件的 ProgID。 |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | 返回物件的 ProgID。 |
| [getLinkFileName()](#getLinkFileName--) | 返回連結檔案的完整路徑。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回連結檔案的完整路徑。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回連結檔案的完整路徑。 |
| [getLinkPathRelative()](#getLinkPathRelative--) | 如果有連結檔案則返回其相對路徑，否則返回空字串。 |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | 返回內嵌 OLE 物件的檔名 |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | 返回內嵌 OLE 物件的路徑 |
| [getEmbeddedData()](#getEmbeddedData--) | 取得或設定 OLE 內嵌資料的資訊。 |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | 設定 OLE 內嵌資料的資訊。 |
| [isObjectIcon()](#isObjectIcon--) | 判斷物件是否以圖示方式顯示。 |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | 判斷物件是否以圖示方式顯示。 |
| [isObjectLink()](#isObjectLink--) | 判斷物件是否連結至外部檔案。 |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | 判斷在開啟或列印簡報時，是否自動更新已連結的內嵌物件。 |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | 判斷在開啟或列印簡報時，是否自動更新已連結的內嵌物件。 |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

返回 OleObject 影像填充屬性物件。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

返回或設定 OleObject 圖示的標題。讀寫 String。

--------------------

當 IsObjectIcon == false 時，此值會被忽略。字串可能會根據 Ole 圖示的大小被截斷。

**返回：**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

返回或設定 OleObject 圖示的標題。讀寫 String。

--------------------

當 IsObjectIcon == false 時，此值會被忽略。字串可能會根據 Ole 圖示的大小被截斷。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

返回或設定物件的名稱。讀寫 String。

**返回：**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

返回或設定物件的名稱。讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

返回物件的 ProgID。唯讀 String。

**返回：**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

返回物件的 ProgID。唯讀 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

返回連結檔案的完整路徑。將使用短檔名。唯讀 String。

**返回：**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

返回連結檔案的完整路徑。將使用長檔名。讀寫 String。

**返回：**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

返回連結檔案的完整路徑。將使用長檔名。讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

如果有連結檔案則返回其相對路徑，否則返回空字串。唯讀 String。

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

--------------------

在 PPT 簡報中，某些 Ole 物件連結可能具有相對表示方式。

**返回：**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

返回內嵌 OLE 物件的檔名

**返回：**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

返回內嵌 OLE 物件的路徑

**返回：**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

取得或設定 OLE 內嵌資料的資訊。讀寫 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)。

**返回：**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

設定 OLE 內嵌資料的資訊。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 內嵌資料 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

此方法會變更物件的屬性以反映新資料，並將 IsObjectLink 標誌設為 false，表示 OLE 物件已嵌入。 |
### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

判斷物件是否以圖示方式顯示。讀寫  boolean 。

**返回：**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

判斷物件是否以圖示方式顯示。讀寫  boolean 。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

判斷物件是否連結至外部檔案。唯讀  boolean 。

**返回：**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

判斷在開啟或列印簡報時，是否自動更新已連結的內嵌物件。讀寫  boolean 。

**返回：**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

判斷在開啟或列印簡報時，是否自動更新已連結的內嵌物件。讀寫  boolean 。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |