---
title: IMathBlock
second_title: Aspose.Slides for Android の Java API リファレンス
description: MathParagraph 内に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。
type: docs
url: /ja/com.aspose.slides/imathblock/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

MathParagraph 内に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。方程式、式、方程式や式の配列、数式など、すべての数式領域は math ブロックで表されます。

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | 子要素すべてを区切り文字で区切ります（ブラケットは含みません）。 |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | このブロックの子要素を、括弧などの指定された文字で囲み、区切り文字で区切ります。 |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 別の数式ブロックをこのブロックに結合します。 |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | この [IMathBlock](../../com.aspose.slides/imathblock) の内容を MathML として保存します。 |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

子要素すべてを区切り文字で区切ります（ブラケットは含みません）。

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char | 区切りとして使用される文字 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - IMathDelimiter 要素のインスタンス
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

このブロックの子要素を、括弧などの指定された文字で囲み、区切り文字で区切ります。

--------------------

> ```
> Example:
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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 型の数式要素で、指定された文字がフレーミングおよび区切り文字として含まれます。
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

別の数式ブロックをこのブロックに結合します。

--------------------

> ```
> Example:
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
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

この [IMathBlock](../../com.aspose.slides/imathblock) の内容を MathML として保存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲットストリーム |