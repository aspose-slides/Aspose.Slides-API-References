---
title: PortionCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 部分のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/portioncollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)  
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

部分のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素の数を取得します。 |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | 指定されたインデックスの要素を取得します。 |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | コレクションの末尾に Portion を追加します。 |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | List 内の特定のアイテムのインデックスを決定します。 |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 指定されたインデックスに Portion を挿入します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。 |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | 特定のオブジェクトの最初の出現を [IGenericCollection](../../com.aspose.slides/igenericcollection) から削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスの要素を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |

### getCount() {#getCount--}
```
public final int getCount()
```

コレクションに実際に含まれる要素の数を取得します。読み取り専用 int。

**戻り値:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。読み取り専用 boolean。

**戻り値:**  
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用の場合は true、そうでない場合は false。

### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IPortion](../../com.aspose.slides/iportion)

### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

コレクションの末尾に Portion を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | コレクションの末尾に追加される Portion。 |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

List 内の特定のアイテムのインデックスを決定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | List で検索するオブジェクト。 |

**戻り値:**  
int - アイテムがリストに見つかった場合のインデックス。それ以外の場合は -1。

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

指定されたインデックスに Portion を挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Portion を挿入する零ベースインデックス。 |
| value | [IPortion](../../com.aspose.slides/iportion) | 挿入する Portion。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての要素を削除します。

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) で検索するオブジェクト。 |

**戻り値:**  
boolean - アイテムが [IGenericCollection](../../com.aspose.slides/igenericcollection) に見つかった場合は true、そうでない場合は false。

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列へコピーします。コピーは特定の配列インデックスから開始します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からコピーされた要素の宛先となる一次元配列です。配列は零ベースインデックスである必要があります。 |
| arrayIndex | int | コピーを開始する配列内の零ベースインデックスです。 |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から削除するオブジェクト。 |

**戻り値:**  
boolean - アイテムが [IGenericCollection](../../com.aspose.slides/igenericcollection) から正常に削除された場合は true、そうでない場合は false。元の [IGenericCollection](../../com.aspose.slides/igenericcollection) にアイテムが見つからない場合も false が返されます。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定されたインデックスの要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素の零ベースインデックス。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - コレクションを反復処理するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - コレクション全体の java.util.Iterator。