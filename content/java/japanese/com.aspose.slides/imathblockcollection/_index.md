---
title: IMathBlockCollection
second_title: Aspose.Slides の Java 用 API リファレンス
description: IMathBlock の数学ブロックのコレクション
type: docs
url: /ja/com.aspose.slides/imathblockcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

数学ブロックのコレクション (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | IMathBlock をコレクションの末尾に追加します。 |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | 指定されたインデックスに IMathBlock をコレクションに挿入します。 |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスにあるアイテムを削除します。 |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | コレクションが特定の値を含んでいるかどうかを判断します。 |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | コレクション内の特定の IMathBlock のインデックスを決定します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれている要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスにあるアイテムを取得します。 |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | 指定されたインデックスにあるアイテムを取得します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

IMathBlock をコレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | コレクションの末尾に追加される数学ブロック |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

指定されたインデックスに IMathBlock をコレクションに挿入します。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | アイテムを挿入すべき0ベースのインデックス。 |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 挿入する IMathBlock。 |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | コレクションから削除するオブジェクト。 |

**戻り値:**
boolean - アイテムがコレクションから正常に削除された場合は true、それ以外の場合は false。元のコレクションにアイテムが見つからない場合も false を返します。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションの指定されたインデックスにあるアイテムを削除します。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するアイテムの0ベースのインデックス。 |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

コレクションが特定の値を含んでいるかどうかを判断します。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | コレクション内で検索するオブジェクト。 |

**戻り値:**
boolean - アイテムがコレクション内に見つかった場合は true、それ以外の場合は false。

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

コレクション内の特定の IMathBlock のインデックスを決定します。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | コレクション内で検索するアイテム。 |

**戻り値:**
int - アイテムがコレクション内に見つかった場合のインデックス。それ以外の場合は -1。

### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクションに実際に含まれている要素数を取得します。読み取り専用 int。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**戻り値:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

指定されたインデックスにあるアイテムを取得します。読み取り専用 [IMathBlock](../../com.aspose.slides/imathblock)。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得するアイテムの0ベースのインデックス。 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 数学テキストのブロック。

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

指定されたインデックスにあるアイテムを取得します。読み取り専用 [IMathBlock](../../com.aspose.slides/imathblock)。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 設定するアイテムの0ベースのインデックス。 |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | 数学テキストのブロック。 |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての要素を削除します。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```
