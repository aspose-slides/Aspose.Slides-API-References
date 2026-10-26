---
title: IConnector
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: コネクタを表します。
type: docs
url: /ja/com.aspose.slides/iconnector/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

コネクタを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | シェイプのロックを返します。 |
| [getConnectorLock()](#getConnectorLock--) | Connector のロックを返します。 |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | コネクタの開始部に接続するシェイプを取得または設定します。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | コネクタの開始部に接続するシェイプを取得または設定します。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | コネクタの終了部に接続するシェイプを取得または設定します。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | コネクタの終了部に接続するシェイプを取得または設定します。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 開始シェイプの接続サイトのインデックスを取得または設定します。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 開始シェイプの接続サイトのインデックスを取得または設定します。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 終了シェイプの接続サイトのインデックスを取得または設定します。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 終了シェイプの接続サイトのインデックスを取得または設定します。 |
| [reroute()](#reroute--) | コネクタを再ルーティングし、接続されるシェイプ間の最短経路を取るようにします。 |

### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

シェイプのロックを返します。 読み取り専用 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**戻り値:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Connector のロックを返します。 読み取り専用 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**戻り値:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

コネクタの開始部に接続するシェイプを取得または設定します。 読み書き [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

コネクタの開始部に接続するシェイプを取得または設定します。 読み書き [IShape](../../com.aspose.slides/ishape)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

コネクタの終了部に接続するシェイプを取得または設定します。 読み書き [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

コネクタの終了部に接続するシェイプを取得または設定します。 読み書き [IShape](../../com.aspose.slides/ishape)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

開始シェイプの接続サイトのインデックスを取得または設定します。 読み書き long。

**戻り値:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

開始シェイプの接続サイトのインデックスを取得または設定します。 読み書き long。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

終了シェイプの接続サイトのインデックスを取得または設定します。 読み書き long。

**戻り値:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

終了シェイプの接続サイトのインデックスを取得または設定します。 読み書き long。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```

コネクタを再ルーティングし、接続されるシェイプ間の最短経路を取るようにします。