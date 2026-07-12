---
title: IMathElementCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 数学要素 MathElement のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/imathelementcollection/
---
**すべての実装インターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

数学要素 (MathElement) のコレクションを表します。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | コレクションの末尾に数学要素を追加します。 |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | コレクション内の特定の数学要素のインデックスを決定します。 |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | 指定されたインデックスに数学要素を挿入します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | コレクションが特定の値を含むかどうかを判定します。 |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスの要素を削除します。 |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | 指定された配列にコピーします。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


指定されたインデックスの要素を取得します。読み取り専用 [IMathElement](../../com.aspose.slides/imathelement)。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得する項目のゼロベースインデックス |

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**戻り値:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


コレクションの末尾に数学要素を追加します。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | コレクションの末尾に追加される IMathElement |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


コレクション内の特定の数学要素のインデックスを決定します。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | コレクション内で検索する要素 |

**戻り値:**
int - アイテムがコレクション内に見つかった場合のインデックス。見つからない場合は -1。
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


指定されたインデックスに数学要素を挿入します。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | IMathElement を挿入すべきゼロベースインデックス |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 挿入する IMathElement |

### clear() {#clear--}
```
public abstract void clear()
```


コレクションからすべての要素を削除します。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```


コレクションが特定の値を含むかどうかを判定します。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | コレクション内で検索するオブジェクト |

**戻り値:**
boolean - アイテムがコレクション内に見つかった場合は true、そうでない場合は false。
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


コレクションから特定のオブジェクトの最初の出現を削除します。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | コレクションから削除するオブジェクト |

**戻り値:**
boolean - アイテムがコレクションから正常に削除された場合は true、そうでない場合は false。アイテムが元のコレクションに存在しなかった場合も false を返します。 
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


コレクションの指定されたインデックスの要素を削除します。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


指定された配列にコピーします。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | コピー先の配列。 |
| arrayIndex | int | コピー開始インデックス。 |