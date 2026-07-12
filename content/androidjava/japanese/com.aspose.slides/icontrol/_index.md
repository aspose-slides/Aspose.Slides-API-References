---
title: IControl
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ActiveX コントロールを表します。
type: docs
url: /ja/com.aspose.slides/icontrol/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

ActiveX コントロールを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | このコントロールの名前を返します。 |
| [setName(String value)](#setName-java.lang.String-) | このコントロールの名前を返します。 |
| [getClassId()](#getClassId--) | このコントロールのクラス ID を取得します。 |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | ControlEx の画像塗りつぶしプロパティオブジェクトを返します。 |
| [getFrame()](#getFrame--) | コントロールのフレームを取得または設定します。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | コントロールのフレームを取得または設定します。 |
| [getProperties()](#getProperties--) | ActiveX プロパティのコレクションを返します。 |
| [getPersistence()](#getPersistence--) | ActiveX コントロールのプロパティを保存するために使用されるメソッドを取得します。 |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | PersistStream、PersistStreamInit、または PersistStorage のいずれかが永続化に使用される場合の ActiveX コントロールの永続性を指定します。 |
### getName() {#getName--}
```
public abstract String getName()
```


このコントロールの名前を返します。 読み書き String.

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


このコントロールの名前を返します。 読み書き String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


このコントロールのクラス ID を取得します。 読み取り専用 java.util.UUID。

**戻り値:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


ControlEx の画像塗りつぶしプロパティオブジェクトを返します。 読み取り専用 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**戻り値:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


コントロールのフレームを取得または設定します。 読み書き [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


コントロールのフレームを取得または設定します。 読み書き [IShapeFrame](../../com.aspose.slides/ishapeframe)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


ActiveX プロパティのコレクションを返します。 読み取り専用 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)。

**戻り値:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


ActiveX コントロールのプロパティを保存するために使用されるメソッドを取得します。 読み取り専用 [PersistenceType](../../com.aspose.slides/persistencetype)。

**戻り値:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


PersistStream、PersistStreamInit、または PersistStorage のいずれかが永続化に使用される場合の ActiveX コントロールの永続性を指定します。

**戻り値:**
byte[]