---
title: OleObjectFrame
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: スライド上の OLE オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/oleobjectframe/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)  
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

スライド上の OLE オブジェクトを表します。

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // PPTX をプレゼンテーション オブジェクトにロードします
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // 最初のスライドにアクセスします
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 形状を OleObjectFrame にキャストします
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // OLE オブジェクトを読み取り、ディスクに書き込みます
>      if (oleObjectFrame != null) {
>          // 埋め込みファイル データを取得します
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // 埋め込みファイルの拡張子を取得します
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // 抽出されたファイルを保存するパスを作成します
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // 抽出したデータを保存します
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject の画像塗りつぶしプロパティオブジェクトを返します。 |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject アイコンのタイトルを取得または設定します。 |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject アイコンのタイトルを取得または設定します。 |
| [getObjectName()](#getObjectName--) | オブジェクトの名前を取得または設定します。 |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | オブジェクトの名前を取得または設定します。 |
| [getObjectProgId()](#getObjectProgId--) | オブジェクトの ProgID を返します。 |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | オブジェクトの ProgID を返します。 |
| [getLinkFileName()](#getLinkFileName--) | リンクされたファイルへのフルパスを返します。 |
| [getLinkPathLong()](#getLinkPathLong--) | リンクされたファイルへのフルパスを返します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | リンクされたファイルへのフルパスを返します。 |
| [getLinkPathRelative()](#getLinkPathRelative--) | 存在すればリンクされたファイルへの相対パスを返し、存在しなければ空文字列を返します。 |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | 埋め込まれた OLE オブジェクトのファイル名を返します。 |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | 埋め込まれた OLE オブジェクトのパスを返します。 |
| [getEmbeddedData()](#getEmbeddedData--) | OLE 埋め込みデータに関する情報を取得または設定します。 |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE 埋め込みデータに関する情報を設定します。 |
| [isObjectIcon()](#isObjectIcon--) | オブジェクトがアイコンとして表示されるかどうかを判断します。 |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | オブジェクトがアイコンとして表示されるかどうかを判断します。 |
| [isObjectLink()](#isObjectLink--) | オブジェクトが外部ファイルにリンクされているかどうかを判断します。 |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | プレゼンテーションが開かれたり印刷されたりしたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判断します。 |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | プレゼンテーションが開かれたり印刷されたりしたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判断します。 |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

OleObject の画像塗りつぶしプロパティオブジェクトを返します。読み取り専用 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**戻り値:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

OleObject アイコンのタイトルを取得または設定します。読み書き可能 String。

--------------------

IsObjectIcon が false の場合、この値は無視されます。文字列は Ole アイコンのサイズに従って切り詰められる場合があります。

**戻り値:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

OleObject アイコンのタイトルを取得または設定します。読み書き可能 String。

--------------------

IsObjectIcon が false の場合、この値は無視されます。文字列は Ole アイコンのサイズに従って切り詰められる場合があります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

オブジェクトの名前を取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

オブジェクトの名前を取得または設定します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

オブジェクトの ProgID を返します。読み取り専用 String。

**戻り値:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

オブジェクトの ProgID を返します。読み取り専用 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

リンクされたファイルへのフルパスを返します。短いファイル名が使用されます。読み取り専用 String。

**戻り値:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

リンクされたファイルへのフルパスを返します。長いファイル名が使用されます。読み書き可能 String。

**戻り値:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

リンクされたファイルへのフルパスを返します。長いファイル名が使用されます。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

存在すればリンクされたファイルへの相対パスを返し、存在しなければ空文字列を返します。読み取り専用 String。

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
public final String getEmbeddedFileLabel()
```

埋め込まれた OLE オブジェクトのファイル名を返します。

**戻り値:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

埋め込まれた OLE オブジェクトのパスを返します。

**戻り値:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

OLE 埋め込みデータに関する情報を取得または設定します。読み書き可能 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)。

**戻り値:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

OLE 埋め込みデータに関する情報を設定します。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

このメソッドはオブジェクトのプロパティを新しいデータに合わせて変更し、IsObjectLink フラグを false に設定します。これにより OLE オブジェクトが埋め込まれたことを示します。

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

オブジェクトがアイコンとして表示されるかどうかを判断します。読み書き可能 boolean。

**戻り値:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

オブジェクトがアイコンとして表示されるかどうかを判断します。読み書き可能 boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

オブジェクトが外部ファイルにリンクされているかどうかを判断します。読み取り専用 boolean。

**戻り値:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

プレゼンテーションが開かれたり印刷されたりしたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判断します。読み書き可能 boolean。

**戻り値:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

プレゼンテーションが開かれたり印刷されたりしたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判断します。読み書き可能 boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |