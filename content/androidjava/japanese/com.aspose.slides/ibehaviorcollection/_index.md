---
title: IBehaviorCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: ビヘイビア効果のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ibehaviorcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

ビヘイビア効果のコレクションを表します。
## メソッド

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのビヘイビアを返します。 |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 指定されたインデックスのビヘイビアを返します。 |
| [getCount()](#getCount--) | コレクション内のビヘイビア数を返します。 |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | コレクションに新しいビヘイビアを追加します。 |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | リスト内の特定の項目のインデックスを決定します。 |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 指定されたインデックスでコレクションに新しいビヘイビアを挿入します。 |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | コレクションから指定されたビヘイビアを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスでコレクションからビヘイビアを削除します。 |
| [clear()](#clear--) | コレクションからすべてのビヘイビアを削除します。 |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

指定されたインデックスのビヘイビアを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 返すビヘイビアのインデックス。 |

**戻り値:**
[IBehavior](../../com.aspose.slides/ibehavior) - アニメーションビヘイビア。

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

指定されたインデックスのビヘイビアを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 返すビヘイビアのインデックス。 |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクション内のビヘイビア数を返します。読み取り専用 int。

**戻り値:**
int

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

コレクションに新しいビヘイビアを追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 追加するビヘイビア。 |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

リスト内の特定の項目のインデックスを決定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | リスト内で検索するオブジェクト。 |

**戻り値:**
int - アイテムがリスト内に見つかった場合のインデックス、見つからない場合は -1。

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

指定されたインデックスでコレクションに新しいビヘイビアを挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいビヘイビアを挿入すべきインデックス。 |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 挿入するビヘイビア。 |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

コレクションから指定されたビヘイビアを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 削除するビヘイビア。 |

**戻り値:**
boolean - True if a behavior removed successfully boolean

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスでコレクションからビヘイビアを削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するビヘイビアのインデックス。 |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのビヘイビアを削除します。

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するオブジェクト。 |

**戻り値:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.