---
title: IPointCollection
second_title: Aspose.Slides for Java API リファレンス
description: 部分のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ipointcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

部分のコレクションを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | コレクション内のポイント数を返します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのポイントを返します。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```


コレクション内のポイント数を返します。 読み取り専用 int。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```


指定されたインデックスのポイントを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint) オブジェクト。