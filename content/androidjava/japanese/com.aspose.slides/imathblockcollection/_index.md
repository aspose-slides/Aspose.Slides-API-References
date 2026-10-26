---
title: IMathBlockCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: IMathBlock の数学ブロックのコレクション
type: docs
url: /ja/com.aspose.slides/imathblockcollection/
---
**実装されているインターフェイス:**  
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
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | コレクションの末尾に IMathBlock を追加します。 |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | 指定されたインデックスに IMathBlock を挿入します。 |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定インデックスにある項目を削除します。 |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | コレクションが特定の値を含むかどうかを判断します。 |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | コレクション内の特定の IMathBlock のインデックスを取得します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定インデックスの項目を取得します。 |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | 指定インデックスの項目を取得します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

コレクションの末尾に IMMathBlock を追加します。

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | コレクションの末尾に追加される数学ブロックです。 |
### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

指定されたインデックスに IMMathBlock を挿入します。

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
| index | int | 項目を挿入すべきゼロベースのインデックスです。 |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 挿入する IMMathBlock。 |
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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | コレクションから削除するオブジェクトです。 |

**戻り値:**
boolean - コレクションから項目が正常に削除された場合は true、そうでない場合は false。元のコレクションに項目が見つからない場合も false を返します。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションの指定インデックスにある項目を削除します。

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
| index | int | 削除する項目のゼロベースインデックスです。 |
### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

コレクションが特定の値を含むかどうかを判断します。

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | コレクション内で検索するオブジェクトです。 |

**戻り値:**
boolean - コレクション内に項目が見つかった場合は true、そうでない場合は false。
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

コレクション内の特定の IMMathBlock のインデックスを取得します。

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | コレクション内で検索する項目です。 |

**戻り値:**
int - コレクション内で項目が見つかった場合のインデックス、見つからない場合は -1。
### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクションに実際に含まれる要素数を取得します。 読み取り専用 int.

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

指定インデックスの項目を取得します。 読み取り専用 [IMathBlock](../../com.aspose.slides/imathblock)。

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
| index | int | 取得する項目のゼロベースインデックスです。 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 数学テキストのブロックです。
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

指定インデックスの項目を取得します。 読み取り専用 [IMathBlock](../../com.aspose.slides/imathblock)。

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
| index | int | 設定する項目のゼロベースインデックスです。 |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | 数学テキストのブロックです。
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