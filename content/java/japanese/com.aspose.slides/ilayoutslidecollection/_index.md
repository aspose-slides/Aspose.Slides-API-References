---
title: ILayoutSlideCollection
second_title: Aspose.Slides for Java API リファレンス
description: レイアウトスライドのコレクションの基底クラスを表します。
type: docs
url: /ja/com.aspose.slides/ilayoutslidecollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

レイアウトスライドのコレクションの基底クラスを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスでレイアウトスライドを取得します。 |
| [getByType(byte type)](#getByType-byte-) | 指定されたタイプの最初のレイアウトスライドを取得します。 |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | コレクションからレイアウトを削除します。 |
| [removeUnused()](#removeUnused--) | 未使用のレイアウトスライドを削除します（HasDependingSlides が false のレイアウトスライド）。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

インデックスでレイアウトスライドを取得します。 読み取り専用 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

指定されたタイプの最初のレイアウトスライドを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | byte | 見つけるレイアウトスライドのタイプ。 |

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 指定されたタイプの [ILayoutSlide](../../com.aspose.slides/ilayoutslide) またはレイアウトが見つからない場合は null。

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

コレクションからレイアウトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | コレクションから削除するレイアウトスライド。 |

--------------------

1) PptxEditException のスローを防ぐために、事前にレイアウトの HasDependingSlides プロパティを確認してください。2) また、[ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) メソッドを使用してコードを簡素化できます。 |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

未使用のレイアウトスライドを削除します（HasDependingSlides が false のレイアウトスライド）。