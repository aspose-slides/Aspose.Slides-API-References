---
title: IDrawingGuidesCollection
second_title: Java APIリファレンスによる Android 用 Aspose.Slides
description: 調整可能な描画ガイドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

調整可能な描画ガイドのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスで描画ガイドを返します。 |
| [add(byte orientation, float position)](#add-byte-float-) | コレクションの末尾に描画ガイドを追加します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの描画ガイドを削除します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [getCount()](#getCount--) | コレクション内のすべての要素数を取得します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

インデックスで描画ガイドを返します。読み取り専用 [IDrawingGuide](../../com.aspose.slides/idrawingguide)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

コレクションの末尾に描画ガイドを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| orientation | byte | 描画ガイドの向き。 |
| position | float | ポイント単位の描画ガイドの位置。 |

**戻り値:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスの描画ガイドを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべき描画ガイドのインデックス。 |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての要素を削除します。

### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクション内のすべての要素数を取得します。読み取り専用 int。

**戻り値:**
int