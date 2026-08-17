---
title: BehaviorCollection
second_title: Aspose.Slides for Java API リファレンス
description: 振る舞い効果のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/behaviorcollection/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)  
```
public class BehaviorCollection implements IBehaviorCollection
```

振る舞いエフェクトのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクション内の振る舞いの数を返します。 |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | コレクションに新しい振る舞いを追加します。 |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | List 内の特定の項目のインデックスを決定します。 |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 指定されたインデックスに新しい振る舞いを挿入します。 |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列にコピーし、特定の配列インデックスから開始します。 |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | コレクションから指定された振る舞いを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの振る舞いをコレクションから削除します。 |
| [clear()](#clear--) | コレクションからすべての振る舞いを削除します。 |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの振る舞いを返します。 |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 指定されたインデックスに振る舞いを設定します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |

### getCount() {#getCount--}
```
public final int getCount()
```

コレクション内の振る舞いの数を返します。 読み取り専用 int.

**戻り値:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 読み取り専用 boolean.

**戻り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用の場合は true、そうでない場合は false。

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

コレクションに新しい振る舞いを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 追加する振る舞い。 |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

List 内の特定の項目のインデックスを決定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | List で検索するオブジェクト。 |

**戻り値:**
int - 項目がリストに見つかった場合はそのインデックス、見つからない場合は -1。

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

指定されたインデックスに新しい振る舞いを挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入先のインデックス。 |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 挿入する振る舞い。 |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列にコピーし、特定の配列インデックスから開始します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からコピーされた要素の宛先となる一次元配列。配列はゼロベースインデックスである必要があります。 |
| arrayIndex | int | コピーを開始する配列内のゼロベースインデックス。 |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

コレクションから指定された振る舞いを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 削除する振る舞い。 |

**戻り値:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスの振る舞いをコレクションから削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する振る舞いのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての振る舞いを削除します。

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection) で検索するオブジェクト。 |

**戻り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) に項目が見つかった場合は true、そうでない場合は false。

### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

指定されたインデックスの振る舞いを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 返す振る舞いのインデックス。 |

**戻り値:**
[IBehavior](../../com.aspose.slides/ibehavior) - アニメーション振る舞い。

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

指定されたインデックスに振る舞いを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 設定する振る舞いのインデックス。 |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - コレクション全体の java.util.Iterator。