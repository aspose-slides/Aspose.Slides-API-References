---
title: IPortionCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: Portion のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/iportioncollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Portion のコレクションを表します。

## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定したインデックスの要素を取得します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Portion をコレクションの末尾に追加します。 |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | コレクション内の特定の Portion のインデックスを決定します。 |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 指定したインデックスに Portion をコレクションに挿入します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。 |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定したインデックスにある要素を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

指定したインデックスの要素を取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**Returns:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Portion をコレクションの末尾に追加します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | コレクションの末尾に追加する Portion。 |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

コレクション内の特定の Portion のインデックスを決定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | コレクション内で検索する Portion。 |

**Returns:**
int - item がコレクションに存在する場合はそのインデックス、存在しない場合は -1。

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

指定したインデックスに Portion をコレクションに挿入します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Portion を挿入するゼロベースのインデックス。 |
| value | [IPortion](../../com.aspose.slides/iportion) | 挿入する Portion。 |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての要素を削除します。

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するオブジェクト。 |

**Returns:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) に item が見つかった場合は true、それ以外は false。

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から削除するオブジェクト。 |

**Returns:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) から item が正常に削除された場合は true、それ以外は false。元の [IGenericCollection](../../com.aspose.slides/igenericcollection) に item が見つからなかった場合も false を返します。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションの指定したインデックスにある要素を削除します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |