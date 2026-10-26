---
title: MathParagraph
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 数式ブロック IMathBlock のコンテナである数式段落
type: docs
url: /ja/com.aspose.slides/mathparagraph/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

数式ブロック (IMathBlock) のコンテナである数式段落

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | MathParagraph クラスの新しいインスタンスを初期化します。 |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | MathParagraph クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification のデフォルト値: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification のデフォルト値: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate オブジェクトを返します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの項目を取得します。 |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | 指定されたインデックスの項目を取得します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | IMathBlock をコレクションの末尾に追加します。 |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | コレクションが特定の値を含むかどうかを判断します。 |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | コレクション内の特定の IMathBlock のインデックスを決定します。 |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | 指定されたインデックスに IMathBlock を挿入します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定インデックスの項目を削除します。 |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | [MathParagraph](../../com.aspose.slides/mathparagraph) の内容を MathML として保存します |
| [toLatex()](#toLatex--) | LaTeX 形式の数式を取得します。 |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```


MathParagraph クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
> ```

### MathParagraph(IMathBlock mathBlock) {#MathParagraph-com.aspose.slides.IMathBlock-}
```
public MathParagraph(IMathBlock mathBlock)
```


MathParagraph クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```


Paragraph Justification のデフォルト値: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**戻り値:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```


Paragraph Justification のデフォルト値: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```


コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```


指定されたインデックスの項目を取得します。読み取り専用 [IMathBlock](../../com.aspose.slides/imathblock)。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得する項目のゼロベースインデックス |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 数学テキストのブロック。
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```


指定されたインデックスの項目を取得します。読み取り専用 [IMathBlock](../../com.aspose.slides/imathblock)。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 取得する項目のゼロベースインデックス |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | 数学テキストのブロック。 |

### clear() {#clear--}
```
public final void clear()
```


コレクションからすべての要素を削除します。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
> ```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```


IMathBlock をコレクションの末尾に追加します。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | コレクションの末尾に追加される数学ブロック |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```


コレクションから特定のオブジェクトの最初の出現を削除します。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | コレクションから削除するオブジェクト。 |

**戻り値:**
boolean - mathBlock がコレクションから正常に削除された場合は true、それ以外の場合は false。このメソッドは元のコレクションに mathBlock が見つからない場合も false を返します。
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```


コレクションが特定の値を含むかどうかを判断します。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | コレクション内で検索するオブジェクト。 |

**戻り値:**
boolean - mathBlock がコレクションに見つかった場合は true、そうでない場合は false。
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```


コレクション内の特定の IMathBlock のインデックスを決定します。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | コレクション内で検索するオブジェクト。 |

**戻り値:**
int - コレクション内で見つかった場合の mathBlock のインデックス。見つからない場合は -1。
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```


指定されたインデックスに IMathBlock を挿入します。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 項目を挿入すべきゼロベースインデックス |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 挿入する IMMathBlock |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


コレクションの指定インデックスの項目を削除します。

--------------------

> ```
> 例:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する項目のゼロベースインデックス |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```


**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```


**戻り値:**
com.aspose.ms.System.Collections.IEnumerator

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


[MathParagraph](../../com.aspose.slides/mathparagraph) の内容を MathML として保存します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### toLatex() {#toLatex--}
```
public final String toLatex()
```


LaTeX 形式の数式を取得します。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**戻り値:**
java.lang.String