---
title: ICellCollection
second_title: Aspose.Slides Android 用 Java API リファレンス
description: セルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/icellcollection/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

セルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定された位置のセルを返します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

指定された位置のセルを返します。読み取り専用 [ICell](../../com.aspose.slides/icell)。

--------------------

セルが結合されている場合、複数のインデックスに対して同じ CellEx オブジェクトが返されることがあります。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ICell](../../com.aspose.slides/icell)