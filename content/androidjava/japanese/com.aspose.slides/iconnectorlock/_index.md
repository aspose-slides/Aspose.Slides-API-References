---
title: IConnectorLock
second_title: Java API リファレンスによる Aspose.Slides for Android
description: 親コネクタで無効になっている操作を判定します。
type: docs
url: /ja/com.aspose.slides/iconnectorlock/
---
**実装されているすべてのインターフェース:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

親コネクタで無効になっている操作を判定します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | このシェイプをグループに追加することが禁止されているかどうかを判定します。 |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | このシェイプをグループに追加することが禁止されているかどうかを判定します。 |
| [getSelectLocked()](#getSelectLocked--) | このシェイプの選択が禁止されているかどうかを判定します。 |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | このシェイプの選択が禁止されているかどうかを判定します。 |
| [getRotateLocked()](#getRotateLocked--) | このシェイプの回転角の変更が禁止されているかどうかを判定します。 |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | このシェイプの回転角の変更が禁止されているかどうかを判定します。 |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | リサイズ時にシェイプがアスペクト比を保持しなければならないかどうかを判定します。 |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | リサイズ時にシェイプがアスペクト比を保持しなければならないかどうかを判定します。 |
| [getPositionMove()](#getPositionMove--) | このシェイプの移動が禁止されているかどうかを判定します。 |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | このシェイプの移動が禁止されているかどうかを判定します。 |
| [getSizeLocked()](#getSizeLocked--) | このシェイプのサイズ変更が禁止されているかどうかを判定します。 |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | このシェイプのサイズ変更が禁止されているかどうかを判定します。 |
| [getEditPointsLocked()](#getEditPointsLocked--) | このシェイプの輪郭の直接変更が禁止されているかどうかを判定します。 |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | このシェイプの輪郭の直接変更が禁止されているかどうかを判定します。 |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | 調整ハンドルの変更が禁止されているかどうかを判定します。 |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | 調整ハンドルの変更が禁止されているかどうかを判定します。 |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | 矢じりの変更が禁止されているかどうかを判定します。 |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | 矢じりの変更が禁止されているかどうかを判定します。 |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | シェイプタイプの変更が禁止されているかどうかを判定します。 |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | シェイプタイプの変更が禁止されているかどうかを判定します。 |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```


このシェイプをグループに追加することが禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```


このシェイプをグループに追加することが禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```


このシェイプの選択が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```


このシェイプの選択が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```


このシェイプの回転角の変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```


このシェイプの回転角の変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```


リサイズ時にシェイプがアスペクト比を保持しなければならないかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```


リサイズ時にシェイプがアスペクト比を保持しなければならないかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```


このシェイプの移動が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```


このシェイプの移動が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```


このシェイプのサイズ変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```


このシェイプのサイズ変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```


このシェイプの輪郭の直接変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```


このシェイプの輪郭の直接変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```


調整ハンドルの変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```


調整ハンドルの変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```


矢じりの変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```


矢じりの変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```


シェイプタイプの変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```


シェイプタイプの変更が禁止されているかどうかを判定します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |