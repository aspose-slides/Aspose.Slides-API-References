---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Represents walls on 3d charts.
type: docs
url: /ja/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

3Dチャートの壁を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getThickness()](#getThickness--) | 壁の厚さをプロット領域の最大次元のパーセンテージとして取得または設定します。 |
| [setThickness(int value)](#setThickness-int-) | 壁の厚さをプロット領域の最大次元のパーセンテージとして取得または設定します。 |
| [getFormat()](#getFormat--) | 壁の塗りつぶし、線、効果、3Dスタイルを取得します。 |
| [getPictureType()](#getPictureType--) | 画像タイプを取得または設定します。 |
| [setPictureType(int value)](#setPictureType-int-) | 画像タイプを取得または設定します。 |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

壁の厚さをプロット領域の最大次元のパーセンテージとして取得または設定します。 読み取り/書き込み int.

**戻り値:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

壁の厚さをプロット領域の最大次元のパーセンテージとして取得または設定します。 読み取り/書き込み int.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

壁の塗りつぶし、線、効果、3Dスタイルを取得します。 読み取り専用 [IFormat](../../com.aspose.slides/iformat).

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

画像タイプを取得または設定します。 読み取り/書き込み [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**戻り値:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

画像タイプを取得または設定します。 読み取り/書き込み [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |