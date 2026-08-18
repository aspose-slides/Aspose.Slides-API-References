---
title: IImage
second_title: Aspose.Slides for Java API リファレンス
description: ラスタまたはベクトル画像を表します。
type: docs
url: /ja/com.aspose.slides/iimage/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

ラスタまたはベクトル画像を表します。

--------------------

このインターフェイスは、ラスタ画像とベクトル画像の両方を扱うための共通抽象化を提供します。実装は基になる画像タイプに応じて異なる場合があります。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | 画像をファイルに保存します。 |
| [save(String filename, int format)](#save-java.lang.String-int-) | 画像を指定された形式でファイルに保存します。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 画像を指定された形式でストリームに保存します。 |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | 画像を指定された形式と品質でファイルに保存します。 |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | 画像を指定された形式と品質でストリームに保存します。 |
| [getSize()](#getSize--) | 画像のサイズを取得します。 |
| [getWidth()](#getWidth--) | 画像の幅（ピクセル）を取得します。 |
| [getHeight()](#getHeight--) | 画像の高さ（ピクセル）を取得します。 |

### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

画像をファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 画像を保存するファイルへのパス。 |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

画像を指定された形式でファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 画像を保存するファイルへのパス。 |
| format | int | 画像形式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

画像を指定された形式でストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 画像が保存されるストリーム。 |
| format | int | 画像形式。 |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

画像を指定された形式と品質でファイルに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | java.lang.String | 画像を保存するファイルへのパス。 |
| format | int | 画像形式。 |
| quality | int | 保存される画像の品質（0〜100）。このパラメーターは [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) での保存にのみ影響し、他のすべての形式では無視されます。 |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

画像を指定された形式と品質でストリームに保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 画像が保存されるストリーム。 |
| format | int | 画像形式。 |
| quality | int | 保存される画像の品質（0〜100）。このパラメーターは [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) での保存にのみ影響し、他のすべての形式では無視されます。 |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

画像のサイズを取得します。

**戻り値:**
java.awt.Dimension

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

画像の幅（ピクセル）を取得します。

**戻り値:**
int

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

画像の高さ（ピクセル）を取得します。

**戻り値:**
int