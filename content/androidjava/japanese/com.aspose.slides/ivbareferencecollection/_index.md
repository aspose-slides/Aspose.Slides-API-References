---
title: IVbaReferenceCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: VBA プロジェクト参照のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ivbareferencecollection/
---
**実装されているすべてのインターフェイス:**  
com.aspose.slides.IGenericCollection
```
public interface IVbaReferenceCollection extends IGenericCollection<IVbaReference>
```

VBA プロジェクト参照のコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | 新しい参照を参照コレクションに追加します |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaReference get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IVbaReference](../../com.aspose.slides/ivbareference)
### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public abstract void add(IVbaReference value)
```

新しい参照を参照コレクションに追加します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) | VBA プロジェクト参照 [IVbaReference](../../com.aspose.slides/ivbareference) |