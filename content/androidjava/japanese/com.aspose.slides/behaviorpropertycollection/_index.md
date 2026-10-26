---
title: BehaviorPropertyCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: エフェクトの動作に対するタイミングプロパティを表します。
type: docs
url: /ja/com.aspose.slides/behaviorpropertycollection/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

エフェクトの動作に対するタイミングプロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに格納されているプロパティの数を返します。 |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | コレクションに新しいプロパティを追加します。 |
| [add(String propertyValue)](#add-java.lang.String-) | コレクションに新しいプロパティを追加します。 |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | リスト内の特定のアイテムのインデックスを決定します。 |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | リスト内でプロパティ値により特定のアイテムのインデックスを決定します。 |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | 指定されたインデックスに新しいプロパティを挿入します。 |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 指定されたインデックスに指定されたプロパティ値を持つ新しいプロパティを挿入します。 |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を特定の配列インデックスから開始して配列にコピーします。 |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | コレクションから指定されたプロパティを削除します。 |
| [remove(String propertyValue)](#remove-java.lang.String-) | コレクションから指定されたプロパティを削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのプロパティを削除します。 |
| [clear()](#clear--) | コレクションからすべてのプロパティを削除します。 |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。 |
| [contains(String propertyValue)](#contains-java.lang.String-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのプロパティを返します。 |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | 指定されたインデックスにプロパティを設定します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |

### size() {#size--}
```
public final int size()
```

コレクションに格納されているプロパティの数を返します。読み取り専用 int。

**戻り値:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。読み取り専用 boolean。

**戻り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用の場合は true。それ以外の場合は false。

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

コレクションに新しいプロパティを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 追加するプロパティ。 |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

コレクションに新しいプロパティを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 追加するプロパティの値。 |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

リスト内の特定のアイテムのインデックスを決定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | リスト内で検索するオブジェクト。 |

**戻り値:**
int - アイテムがリストに見つかった場合のインデックス。それ以外の場合は -1。

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

リスト内でプロパティ値により特定のアイテムのインデックスを決定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | プロパティの値 |

**戻り値:**
int - 指定された値を持つプロパティのインデックス。

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

指定されたインデックスに新しいプロパティを挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいプロパティを挿入すべきインデックス。 |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 追加するプロパティ。 |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

指定されたインデックスに指定されたプロパティ値を持つ新しいプロパティを挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいプロパティを挿入すべきインデックス。 |
| propertyValue | java.lang.String | 追加するプロパティの値。 |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を特定の配列インデックスから開始して配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からコピーされた要素の宛先となる一次元配列。配列は0から始まるインデックスを持つ必要があります。 |
| arrayIndex | int | コピーを開始する配列内の0ベースインデックス。 |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

コレクションから指定されたプロパティを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 削除するプロパティ。 |

**戻り値:**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

コレクションから指定されたプロパティを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 削除するプロパティの値。 |

**戻り値:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのプロパティを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべきプロパティのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのプロパティを削除します。

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するプロパティ。 |

**戻り値:**
boolean - item が [IGenericCollection](../../com.aspose.slides/igenericcollection) に見つかった場合は true。そうでない場合は false。

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するプロパティの値。 |

**戻り値:**
boolean - propertyValue が [IGenericCollection](../../com.aspose.slides/igenericcollection) に見つかった場合は true。そうでない場合は false。

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

指定されたインデックスのプロパティを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 返すプロパティのインデックス。 |

**戻り値:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - アニメーション ビヘイビア プロパティ。

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

指定されたインデックスにプロパティを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 設定するプロパティのインデックス。 |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - コレクションを反復処理するために使用できる IGenericEnumerator。

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**戻り値:**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**戻り値:**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**戻り値:**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - コレクション全体の java.util.Iterator。