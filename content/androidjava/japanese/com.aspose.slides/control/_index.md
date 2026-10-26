---
title: Control
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ActiveX コントロールを表します。
type: docs
url: /ja/com.aspose.slides/control/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)  
```
public class Control extends DomObject<ControlCollection> implements IControl
```

ActiveX コントロールを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPersistence()](#getPersistence--) | ActiveX コントロールのプロパティを保存するために使用されるメソッドを取得します。 |
| [getName()](#getName--) | このコントロールの名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | このコントロールの名前を取得または設定します。 |
| [getClassId()](#getClassId--) | このコントロールのクラス ID を取得します。 |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | このコントロールのクラス ID を取得します。 |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Control の画像塗りつぶしプロパティ オブジェクトを返します。 |
| [getFrame()](#getFrame--) | コントロールのフレームを取得または設定します。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | コントロールのフレームを取得または設定します。 |
| [getProperties()](#getProperties--) | ActiveX プロパティのコレクションを返します。 |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | 永続化に使用されるメソッドが PersistStream、PersistStreamInit、または PersistStorage のいずれかの場合の ActiveX コントロールの永続性を指定します。 |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

ActiveX コントロールのプロパティを保存するために使用されるメソッドを取得します。読み取り専用 [PersistenceType](../../com.aspose.slides/persistencetype)。

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
>      YourMethodHere(control.getActiveXControlBinary()); //自分のメソッドを使用して、バイナリ ファイルに保存された ActiveX プロパティを管理します
>  }
> ```

**戻り値:**  
int

### getName() {#getName--}
```
public final String getName()
```

このコントロールの名前を取得または設定します。読み書き可能 String。

**戻り値:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

このコントロールの名前を取得または設定します。読み書き可能 String。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

このコントロールのクラス ID を取得します。読み取り専用 java.util.UUID。

**戻り値:**  
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

このコントロールのクラス ID を取得します。読み取り専用 java.util.UUID。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Control の画像塗りつぶしプロパティ オブジェクトを返します。読み取り専用 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**戻り値:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

コントロールのフレームを取得または設定します。読み書き可能 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**戻り値:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

コントロールのフレームを取得または設定します。読み書き可能 [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

ActiveX プロパティのコレクションを返します。読み取り専用 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)。

--------------------

注意: Aspose.Slides は XML ベースの ActiveX プロパティのみをサポートします。プロパティがバイナリ形式で保存されている場合、このプロパティは null を返します。

**戻り値:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

永続化に使用されるメソッドが PersistStream、PersistStreamInit、または PersistStorage のいずれかの場合の ActiveX コントロールの永続性を指定します。

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
>      YourMethodHere(control.getActiveXControlBinary()); //バイナリ ファイルに保存された ActiveX プロパティを管理するために独自のメソッドを使用してください
>  }
> ```

**戻り値:**  
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ベース スライドを返します。読み取り専用 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**戻り値:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**  
[IPresentation](../../com.aspose.slides/ipresentation)