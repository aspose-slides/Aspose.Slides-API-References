---
title: ITrendlineCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: TrendlineEx のコレクションを表します
type: docs
url: /ja/com.aspose.slides/itrendlinecollection/
---
**実装されているすべてのインターフェイス:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable  
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

TrendlineEx のコレクションを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [add(int trendlineType)](#add-int-) | コレクションの末尾に新しい Trendline を追加し、返します。 |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 指定された値を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [ITrendline](../../com.aspose.slides/itrendline)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

コレクションの末尾に新しい Trendline を追加し、返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| trendlineType | int | Trendline のタイプ [TrendlineType](../../com.aspose.slides/trendlinetype) |

**戻り値:**
[ITrendline](../../com.aspose.slides/itrendline) - 新しい Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

指定された値を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | 削除する Trendline [ITrendline](../../com.aspose.slides/itrendline) |