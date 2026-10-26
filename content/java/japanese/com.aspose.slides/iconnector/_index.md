---
title: IConnector
second_title: Aspose.Slides の Java API リファレンス
description: コネクタを表します。
type: docs
url: /ja/com.aspose.slides/iconnector/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Represents a connector.  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | shape のロックを返します。 |
| [getConnectorLock()](#getConnectorLock--) | Connector のロックを返します。 |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | connector の開始点に接続する shape を取得または設定します。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | connector の開始点に接続する shape を取得または設定します。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | connector の終了点に接続する shape を取得または設定します。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | connector の終了点に接続する shape を取得または設定します。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 開始 shape の接続サイトのインデックスを取得または設定します。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 開始 shape の接続サイトのインデックスを取得または設定します。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 終了 shape の接続サイトのインデックスを取得または設定します。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 終了 shape の接続サイトのインデックスを取得または設定します。 |
| [reroute()](#reroute--) | connector が接続する shape 間の最短パスになるように再ルーティングします。 |

### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

shape のロックを返します。読み取り専用 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**戻り値:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Connector のロックを返します。読み取り専用 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**戻り値:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

connector の開始点に接続する shape を取得または設定します。読み書き可能 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**  
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

connector の開始点に接続する shape を取得または設定します。読み書き可能 [IShape](../../com.aspose.slides/ishape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

connector の終了点に接続する shape を取得または設定します。読み書き可能 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**  
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

connector の終了点に接続する shape を取得または設定します。読み書き可能 [IShape](../../com.aspose.slides/ishape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

開始 shape の接続サイトのインデックスを取得または設定します。読み書き可能 long。

**戻り値:**  
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

開始 shape の接続サイトのインデックスを取得または設定します。読み書き可能 long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

終了 shape の接続サイトのインデックスを取得または設定します。読み書き可能 long。

**戻り値:**  
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

終了 shape の接続サイトのインデックスを取得または設定します。読み書き可能 long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```

connector が接続する shape 間の最短パスになるように再ルーティングします。