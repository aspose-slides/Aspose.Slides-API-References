---
title: MathBlock
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: MathParagraph に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。
type: docs
url: /ja/com.aspose.slides/mathblock/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

MathParagraph 内に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。数式ブロックは、方程式、式、方程式や式の配列、そして数式を含むすべての数式領域を表します。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathBlock()](#MathBlock--) | MathBlock クラスの新しいインスタンスを初期化します。 |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | 新しい数式ブロックを作成し、指定された要素を配置します |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 新しい数式ブロックを作成し、指定された要素を配置します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクションに実際に含まれる子数式要素の数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの IMathElement を取得または設定します。 |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | 指定されたインデックスの IMathElement を取得または設定します。 |
| [isReadOnly()](#isReadOnly--) | 子要素コレクションは変更可能であるため false を返します。 |
| [getChildren()](#getChildren--) | 子要素を取得します |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate オブジェクトを返します。 |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | コレクションの末尾に数式要素を追加します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | コレクションが特定の値を含むかどうかを判定します。 |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | 指定された配列へコピーします。 |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | コレクション内の特定の数式要素のインデックスを判定します。 |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | 指定されたインデックスに MathElement を挿入します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定インデックスの要素を削除します。 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | この数式ブロックに数式要素を結合します |
| [join(String mathText)](#join-java.lang.String-) | この数式ブロックに数式テキストを結合します |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 別の数式ブロックをこれと結合します |
| [delimit(char separatorCharacter)](#delimit-char-) | 子要素を区切り文字で区切ります（括弧は除く） |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | このブロックの子要素を括弧などの指定文字で囲みます |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | このブロックの子要素を指定文字で囲み、区切り文字で区切ります |
| [toMathArray()](#toMathArray--) | 子要素を縦方向の配列に配置します |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | この [MathBlock](../../com.aspose.slides/mathblock) の内容を MathML として保存します |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

MathBlock クラスの新さいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

新しい数式ブロックを作成し、指定された要素を配置します

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | ブロックに配置する数式要素 |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

新しい数式ブロックを作成し、指定された要素を配置します

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | ブロックに配置する数式要素 |

### getCount() {#getCount--}
```
public final int getCount()
```

コレクションに実際に含まれる子数式要素の数を取得します。読み取り専用 int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

指定されたインデックスの IMathElement を取得または設定します。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | アイテムのゼロベースインデックス |

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement) - 数式要素。

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

指定されたインデックスの IMathElement を取得または設定します。

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | アイテムのゼロベースインデックス |
| value | [IMathElement](../../com.aspose.slides/imathelement) | 数式要素。 |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

子要素コレクションは変更可能であるため false を返します。

**戻り値:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得します

**戻り値:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

コレクションの末尾に数式要素を追加します。

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | コレクションの末尾に追加する IMathElement。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての要素を削除します。

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```


### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

コレクションが特定の値を含むかどうかを判定します。

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | コレクション内で検索するオブジェクト。 |

**戻り値:**
boolean - アイテムがコレクション内に見つかった場合は true、そうでない場合は false。

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

指定された配列へコピーします。

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | コピー先配列。 |
| arrayIndex | int | コピー開始インデックス。 |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | コレクションから削除するオブジェクト。 |

**戻り値:**
boolean - アイテムが正常に削除された場合は true、そうでない場合は false。このメソッドは、元のコレクションにアイテムが存在しない場合も false を返します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.IEnumerator - コレクション全体の java.util.Iterator。

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

コレクション内の特定の数式要素のインデックスを判定します。

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | コレクション内で検索する要素。 |

**戻り値:**
int - アイテムが見つかった場合はそのインデックス、見つからない場合は -1。

### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

指定されたインデックスに MathElement を挿入します。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | MathElement を挿入するゼロベースインデックス。 |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 挿入する MathElement。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定インデックスの要素を削除します。

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

この数式ブロックに数式要素を結合します

--------------------

> ```
> 例:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 結合する要素 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 現在の IMathBlock インスタンス

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

この数式ブロックに数式テキストを結合します

--------------------

> ```
> 例:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | 結合する数式テキスト |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - このインスタンスと指定引数を含む新しい IMathBlock

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

別の数式ブロックをこれと結合します

--------------------

> ```
> 例:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | 結合するブロック |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 結合後のこの数式ブロック

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

子要素を区切り文字で区切ります（括弧は除く）

--------------------

> ```
> 例:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char | 区切り文字 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 型 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) の数式要素

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

このブロックの子要素を括弧などの指定文字で囲みます

--------------------

> ```
> 例:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char | 開始文字（通常は左括弧） |
| endingCharacter | char | 終了文字（通常は右括弧） |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 指定文字で枠取された型 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) の数式要素

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

このブロックの子要素を指定文字で囲み、区切り文字で区切ります

--------------------

> ```
> 例:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char | 開始文字（通常は左括弧） |
| endingCharacter | char | 終了文字（通常は右括弧） |
| separatorCharacter | char | 区切り文字 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 指定文字で枠取され、区切り文字で区切られた型 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) の数式要素

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

子要素を縦方向の配列に配置します

--------------------

> ```
> 例:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**戻り値:**
[IMathArray](../../com.aspose.slides/imatharray) - 型 [IMathArray](../../com.aspose.slides/imatharray) の新しいインスタンス

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

この [MathBlock](../../com.aspose.slides/mathblock) の内容を MathML として保存します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲットストリーム |