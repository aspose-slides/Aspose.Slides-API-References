---
title: Connector
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: コネクタを表します。
type: docs
url: /ja/com.aspose.slides/connector/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**実装されているすべてのインターフェイス:**
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
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | コネクタの開始部に接続するシェイプを取得または設定します。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | コネクタの開始部に接続するシェイプを取得または設定します。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | コネクタの終了部に接続するシェイプを取得または設定します。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | コネクタの終了部に接続するシェイプを取得または設定します。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 開始シェイプの接続サイトインデックスを取得または設定します。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 開始シェイプの接続サイトインデックスを取得または設定します。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 終了シェイプの接続サイトインデックスを取得または設定します。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 終了シェイプの接続サイトインデックスを取得または設定します。 |
| [reroute()](#reroute--) | コネクタを再ルーティングし、接続するシェイプ間の最短経路を取るようにします。 |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


シェイプのロックを返します。読み取り専用 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**戻り値:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


コネクタのロックを返します。読み取り専用 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**戻り値:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


AutoShape のタイプを取得または設定します。読み書き [ShapeType](../../com.aspose.slides/shapetype)。

**戻り値:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


AutoShape のタイプを取得または設定します。読み書き [ShapeType](../../com.aspose.slides/shapetype)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


コネクタの開始部に接続するシェイプを取得または設定します。読み書き [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


コネクタの開始部に接続するシェイプを取得または設定します。読み書き [IShape](../../com.aspose.slides/ishape)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


コネクタの終了部に接続するシェイプを取得または設定します。読み書き [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


コネクタの終了部に接続するシェイプを取得または設定します。読み書き [IShape](../../com.aspose.slides/ishape)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


開始シェイプの接続サイトインデックスを取得または設定します。読み書き long。

**戻り値:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


開始シェイプの接続サイトインデックスを取得または設定します。読み書き long。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


終了シェイプの接続サイトインデックスを取得または設定します。読み書き long。

**戻り値:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


終了シェイプの接続サイトインデックスを取得または設定します。読み書き long。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```


コネクタを再ルーティングし、接続するシェイプ間の最短経路を取るようにします。