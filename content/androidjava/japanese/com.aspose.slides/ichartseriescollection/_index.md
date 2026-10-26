---
title: IChartSeriesCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: コレクションを表します
type: docs
url: /ja/com.aspose.slides/ichartseriescollection/
---
**実装されたすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

[IChartSeries](../../com.aspose.slides/ichartseries) のコレクションを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [add(int type)](#add-int-) | 新しいチャートシリーズを作成し、コレクションに追加します。 |
| [insert(int index, int type)](#insert-int-int-) | 新しいチャートシリーズを作成し、コレクションに挿入します。 |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | [IChartDataCell](../../com.aspose.slides/ichartdatacell) から新しいチャートシリーズを作成し、コレクションに追加します。 |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) から新しいチャートシリーズを作成し、コレクションに追加します。 |
| [add(String name, int type)](#add-java.lang.String-int-) | 値から新しいチャートシリーズを作成し、コレクションに追加します。 |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | [IChartSeries](../../com.aspose.slides/ichartseries) を検索し、コレクション全体で最初に出現する位置のゼロベースインデックスを返します。 |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 指定された値を削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの要素を削除します |
| [clear()](#clear--) | コレクションからすべての要素（チャートスタイルを含む）を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 指定されたインデックスの要素です。
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

新しいチャートシリーズを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | シリーズのタイプ |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新しいチャートシリーズです。
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

新しいチャートシリーズを作成し、コレクションに挿入します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 挿入位置のインデックス int |
| type | int | チャートタイプ [ChartType](../../com.aspose.slides/charttype) |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新しいチャートシリーズ [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

[IChartDataCell](../../com.aspose.slides/ichartdatacell) から新しいチャートシリーズを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | シリーズ名を含むセル |
| type | int | シリーズのタイプを設定 |

--------------------

もし同じセルから作成されたチャートシリーズがすでにコレクションに存在する場合、メソッドは何も追加せず、そのインデックスを返します。 |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 追加されたチャートシリーズ、またはすでにコレクションにあるシリーズです。
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) から新しいチャートシリーズを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | シリーズ名を含むセル |
| type | int | シリーズのタイプを設定 |

--------------------

もし同じセルから作成されたチャートシリーズがすでにコレクションに存在する場合、メソッドは何も追加せず、そのインデックスを返します。 |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 追加されたチャートシリーズ、またはすでにコレクションにあるシリーズです。
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

値から新しいチャートシリーズを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | シリーズ名 |
| type | int | シリーズのタイプを設定 |

**戻り値:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 追加されたチャートシリーズです。
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

[IChartSeries](../../com.aspose.slides/ichartseries) を検索し、コレクション全体で最初に出現する位置のゼロベースインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | チャートシリーズの値 |

**戻り値:**
int - 値がコレクションベース全体で最初に出現する位置のゼロベースインデックス（見つかった場合）。見つからない場合は -1。
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

指定された値を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 値 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスの要素を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | インデックス int |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての要素（チャートスタイルを含む）を削除します。