---
title: IControlCollection
second_title: Aspose.Slides の Java API リファレンス
description: ActiveX コントロールのコレクションです。
type: docs
url: /ja/com.aspose.slides/icontrolcollection/
---
**すべての実装済みインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

ActiveX コントロールのコレクションです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | コレクションから ActiveX コントロールを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定された位置に格納されている ActiveX コントロールをコレクションから削除します。 |
| [clear()](#clear--) | コレクション内のすべてのコントロールを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定された位置にあるコントロールを返します。 |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | 新しいコントロールを作成し、コレクションに追加します。 |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

コレクションから ActiveX コントロールを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 削除するコントロールです。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定された位置に格納されている ActiveX コントロールをコレクションから削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するコントロールのインデックスです。 |

### clear() {#clear--}
```
public abstract void clear()
```

コレクション内のすべてのコントロールを削除します。

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

指定された位置にあるコントロールを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | コントロールのインデックスです。 |

**戻り値:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

新しいコントロールを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| controlType | int | 追加するコントロールの種類です。 |
| x | float | シェイプのフレーム左側の X 座標です。 |
| y | float | シェイプのフレーム上側の Y 座標です。 |
| width | float | シェイプのフレームの幅です。 |
| height | float | シェイプのフレームの高さです。 |

**戻り値:**
[IControl](../../com.aspose.slides/icontrol) - 作成されたコントロール [IControl](../../com.aspose.slides/icontrol).