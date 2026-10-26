---
title: ITextAnimationCollection
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: テキスト アニメーションのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/itextanimationcollection/
---
**実装されているすべてのインターフェイス:**  
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

テキスト アニメーションのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスで要素を返します。 |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | すべての要素を返します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```

インデックスで要素を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```

すべての要素を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) 要素。 |

**戻り値:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) の配列