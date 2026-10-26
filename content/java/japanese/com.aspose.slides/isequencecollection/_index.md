---
title: ISequenceCollection
second_title: Aspose.Slides の Java API リファレンス
description: インタラクティブシーケンスのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/isequencecollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

インタラクティブシーケンスのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクション内の要素数を返します Read-only int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | 新しいインタラクティブシーケンスを追加します。 |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | コレクションから指定されたシーケンスを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定したインデックスのシーケンスを削除します。 |
| [clear()](#clear--) | コレクションからすべてのシーケンスを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定したインデックスのシーケンスを返します。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクション内の要素数を返します Read-only int.

**戻り値:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

新しいインタラクティブシーケンスを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape オブジェクト [IShape](../../com.aspose.slides/ishape) |

**戻り値:**
[ISequence](../../com.aspose.slides/isequence) - 新しいシーケンス [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

コレクションから指定されたシーケンスを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | 削除するシーケンス。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定したインデックスのシーケンスを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | コレクション内の要素のインデックス int |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのシーケンスを削除します。

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

指定したインデックスのシーケンスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) オブジェクト。