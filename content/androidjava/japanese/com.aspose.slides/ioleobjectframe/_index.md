---
title: IOleObjectFrame
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド上の OLE オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/ioleobjectframe/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

スライド上のOLEオブジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject の画像塗りつぶしプロパティ オブジェクトを返します。 |
| [getObjectName()](#getObjectName--) | オブジェクトの名前を取得または設定します。 |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | オブジェクトの名前を取得または設定します。 |
| [getEmbeddedData()](#getEmbeddedData--) | OLE 埋め込みデータに関する情報を取得します。 |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE 埋め込みデータに関する情報を設定します。 |
| [getObjectProgId()](#getObjectProgId--) | オブジェクトの ProgID を返します。 |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | オブジェクトの ProgID を返します。 |
| [getLinkFileName()](#getLinkFileName--) | リンクされたファイルへのフルパスを返します。 |
| [getLinkPathLong()](#getLinkPathLong--) | リンクされたファイルへのフルパスを返します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | リンクされたファイルへのフルパスを返します。 |
| [getLinkPathRelative()](#getLinkPathRelative--) | 存在する場合はリンクされたファイルへの相対パスを返し、存在しない場合は空文字列を返します。 |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | 埋め込み OLE オブジェクトのファイル名を返します |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | 埋め込み OLE オブジェクトのパスを返します |
| [isObjectIcon()](#isObjectIcon--) | オブジェクトがアイコンとして表示されるかどうかを判定します。 |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | オブジェクトがアイコンとして表示されるかどうかを判定します。 |
| [isObjectLink()](#isObjectLink--) | オブジェクトが外部ファイルにリンクされているかどうかを判定します。 |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | プレゼンテーションが開かれたり印刷されたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判定します。 |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | プレゼンテーションが開かれたり印刷されたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判定します。 |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject アイコンのタイトルを取得または設定します。 |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject アイコンのタイトルを取得または設定します。 |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


OleObject の画像塗りつぶしプロパティ オブジェクトを返します。読み取り専用 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**戻り値:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


オブジェクトの名前を取得または設定します。読み書き String。

**戻り値:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


オブジェクトの名前を取得または設定します。読み書き String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


OLE 埋め込みデータに関する情報を取得します。読み取り専用 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)。

**戻り値:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


OLE 埋め込みデータに関する情報を設定します。

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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 埋め込みデータ [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

このメソッドは、オブジェクトのプロパティを新しいデータに合わせて変更し、IsObjectLink フラグを false に設定して OLE オブジェクトが埋め込まれていることを示します。 |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


オブジェクトの ProgID を返します。読み取り専用 String。

**戻り値:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


オブジェクトの ProgID を返します。読み取り専用 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


リンクされたファイルへのフルパスを返します。短いファイル名が使用されます。読み取り専用 String。

**戻り値:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


リンクされたファイルへのフルパスを返します。長いファイル名が使用されます。読み書き String。

**戻り値:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


リンクされたファイルへのフルパスを返します。長いファイル名が使用されます。読み書き String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```


存在する場合はリンクされたファイルへの相対パスを返し、存在しない場合は空文字列を返します。読み取り専用 String。

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

Ppt プレゼンテーションでは、一部の Ole オブジェクトリンクが相対表現になることがあります。

**戻り値:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


埋め込み OLE オブジェクトのファイル名を返します

**戻り値:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


埋め込み OLE オブジェクトのパスを返します

**戻り値:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


オブジェクトがアイコンとして表示されるかどうかを判定します。読み書き boolean。

**戻り値:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


オブジェクトがアイコンとして表示されるかどうかを判定します。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


オブジェクトが外部ファイルにリンクされているかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


プレゼンテーションが開かれたり印刷されたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判定します。読み書き boolean。

**戻り値:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


プレゼンテーションが開かれたり印刷されたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判定します。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


OleObject アイコンのタイトルを取得または設定します。読み書き String。

--------------------

IsObjectIcon が false の場合、この値は無視されます。文字列は OLE アイコンのサイズに合わせて切り詰められる可能性があります。

**戻り値:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


OleObject アイコンのタイトルを取得または設定します。読み書き String。

--------------------

IsObjectIcon が false の場合、この値は無視されます。文字列は OLE アイコンのサイズに合わせて切り詰められる可能性があります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |