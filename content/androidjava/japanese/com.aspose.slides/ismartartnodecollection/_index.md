---
title: ISmartArtNodeCollection
second_title: Java APIリファレンスによる Android 向け Aspose.Slides
description: SmartArt ノードのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ismartartnodecollection/
---
**実装されているすべてのインターフェイス:**  
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

SmartArt ノードのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスでノードを返します。 |
| [addNode()](#addNode--) | 新しいノードまたはサブノードを追加します。 |
| [removeNode(int index)](#removeNode-int-) | インデックスでノードまたはサブノードを削除します。 |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | ノードまたはサブノードを削除します。 |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | ノードコレクションの選択された位置に新しいノードを追加します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

インデックスでノードを返します。読み取り専用 [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のゼロベースインデックス。 |

**戻り値:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

新しいノードまたはサブノードを追加します。

**戻り値:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 追加されたノード
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

インデックスでノードまたはサブノードを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | ノードのゼロベースインデックス |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

ノードまたはサブノードを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 削除するノード。 |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

ノードコレクションの選択された位置に新しいノードを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | int | ゼロベースのノード位置。 |

**戻り値:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 追加されたノード