---
title: IControlCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: ActiveX コントロールのコレクションです。
type: docs
url: /ja/com.aspose.slides/icontrolcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

ActiveX コントロールのコレクションです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | コレクションから ActiveX コントロールを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定された位置に格納された ActiveX コントロールをコレクションから削除します。 |
| [clear()](#clear--) | コレクションからすべてのコントロールを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定された位置のコントロールを返します。 |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | コレクションに新しいコントロールを作成して追加します。 |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

コレクションから ActiveX コントロールを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 削除するコントロール。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定された位置に格納された ActiveX コントロールをコレクションから削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するコントロールのインデックス。 |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのコントロールを削除します。

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

指定された位置のコントロールを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | コントロールのインデックス。 |

**戻り値:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

コレクションに新しいコントロールを作成して追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| controlType | int | 追加するコントロールのタイプ。 |
| x | float | シェイプのフレームの左側の X 座標。 |
| y | float | シェイプのフレームの上側の Y 座標。 |
| width | float | シェイプのフレームの幅。 |
| height | float | シェイプのフレームの高さ。 |

**戻り値:**
[IControl](../../com.aspose.slides/icontrol) - 作成されたコントロール [IControl](../../com.aspose.slides/icontrol)。