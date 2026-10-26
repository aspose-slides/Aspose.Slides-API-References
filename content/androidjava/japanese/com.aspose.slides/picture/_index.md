---
title: Picture
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: プレゼンテーション内の画像を表します。
type: docs
url: /ja/com.aspose.slides/picture/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

プレゼンテーション内の画像を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | 埋め込み画像を取得または設定します。 |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | 埋め込み画像を取得または設定します。 |
| [getLinkPathLong()](#getLinkPathLong--) | リンクされた画像の URL を取得または設定します。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | リンクされた画像の URL を取得または設定します。 |
| [getImageTransform()](#getImageTransform--) | 画像変換エフェクトのコレクションを返します。 |
| [getPresentation()](#getPresentation--) | プレゼンテーションを返します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトと比較します。 |
| [hashCode()](#hashCode--) | ハッシュを返します。 |
| [getSlide()](#getSlide--) | 画像の親スライドを返します。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


バージョン。 読み取り専用 long。

**戻り値:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


親 IPresentationComponent を返します。 読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```


埋め込み画像を取得または設定します。 読み書き [IPPImage](../../com.aspose.slides/ippimage)。

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```


埋め込み画像を取得または設定します。 読み書き [IPPImage](../../com.aspose.slides/ippimage)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


リンクされた画像の URL を取得または設定します。 読み書き String。

**戻り値:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


リンクされた画像の URL を取得または設定します。 読み書き String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```


画像変換エフェクトのコレクションを返します。 読み取り専用 [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)。

**戻り値:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


プレゼンテーションを返します。 読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトと比較します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象のオブジェクト。 |

**戻り値:**
boolean - 等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


ハッシュを返します。

**戻り値:**
int - ハッシュ。
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


画像の親スライドを返します。 読み取り専用 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)