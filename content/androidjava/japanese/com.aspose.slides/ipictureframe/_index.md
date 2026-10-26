---
title: IPictureFrame
second_title: Aspose.Slides for Android の Java API リファレンス
description: 画像を内部に含むフレームを表します。
type: docs
url: /ja/com.aspose.slides/ipictureframe/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

画像を内部に含むフレームを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | PictureFrame のロックを返します。 |
| [getPictureFormat()](#getPictureFormat--) | 画像フレームの PictureFillFormat オブジェクトを返します。 |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 画像フレームの高さのスケール (元の画像サイズに対する相対) を取得または設定します。 |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 画像フレームの高さのスケール (元の画像サイズに対する相対) を取得または設定します。 |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 画像フレームの幅のスケール (元の画像サイズに対する相対) を取得または設定します。 |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 画像フレームの幅のスケール (元の画像サイズに対する相対) を取得または設定します。 |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```


PictureFrame のロックを返します。読み取り専用 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)。

**戻り値:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```


画像フレームの PictureFillFormat オブジェクトを返します。読み取り専用 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**戻り値:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```


画像フレームの高さのスケール (元の画像サイズに対する相対) を取得または設定します。値 1.0 は 100% に相当します。読み書き可能な float。

**戻り値:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```


画像フレームの高さのスケール (元の画像サイズに対する相対) を取得または設定します。値 1.0 は 100% に相当します。読み書き可能な float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```


画像フレームの幅のスケール (元の画像サイズに対する相対) を取得または設定します。値 1.0 は 100% に相当します。読み書き可能な float。

**戻り値:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```


画像フレームの幅のスケール (元の画像サイズに対する相対) を取得または設定します。値 1.0 は 100% に相当します。読み書き可能な float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |