---
title: Connector
second_title: Aspose.Slides for Java API リファレンス
description: コネクタを表します。
type: docs
url: /ja/com.aspose.slides/connector/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

コネクタを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | シェイプのロックを返します。 |
| [getConnectorLock()](#getConnectorLock--) | コネクタのロックを返します。 |
| [getShapeType()](#getShapeType--) | AutoShape のタイプを取得または設定します。 |
| [setShapeType(int value)](#setShapeType-int-) | AutoShape のタイプを取得または設定します。 |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | コネクタの開始側に接続するシェイプを取得または設定します。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | コネクタの開始側に接続するシェイプを取得または設定します。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | コネクタの終端に接続するシェイプを取得または設定します。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | コネクタの終端に接続するシェイプを取得または設定します。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 開始シェイプの接続サイトのインデックスを取得または設定します。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 開始シェイプの接続サイトのインデックスを取得または設定します。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 終了シェイプの接続サイトのインデックスを取得または設定します。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 終了シェイプの接続サイトのインデックスを取得または設定します。 |
| [reroute()](#reroute--) | コネクタを再ルーティングし、接続するシェイプ間の最短パスを取るようにします。 |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


シェイプのロックを返します。 読み取り専用 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**戻り値:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


コネクタのロックを返します。 読み取り専用 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**戻り値:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


AutoShape のタイプを取得または設定します。 読み取り/書き込み [ShapeType](../../com.aspose.slides/shapetype)。

**戻り値:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


AutoShape のタイプを取得または設定します。 読み取り/書き込み [ShapeType](../../com.aspose.slides/shapetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


開始側に接続するシェイプを取得または設定します。 読み取り/書き込み [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


開始側に接続するシェイプを取得または設定します。 読み取り/書き込み [IShape](../../com.aspose.slides/ishape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


終了側に接続するシェイプを取得または設定します。 読み取り/書き込み [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


終了側に接続するシェイプを取得または設定します。 読み取り/書き込み [IShape](../../com.aspose.slides/ishape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


開始シェイプの接続サイトのインデックスを取得または設定します。 読み取り/書き込み long。

**戻り値:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


開始シェイプの接続サイトのインデックスを取得または設定します。 読み取り/書き込み long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


終了シェイプの接続サイトのインデックスを取得または設定します。 読み取り/書き込み long。

**戻り値:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


終了シェイプの接続サイトのインデックスを取得または設定します。 読み取り/書き込み long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```


コネクタを再ルーティングし、接続するシェイプ間の最短パスを取るようにします。