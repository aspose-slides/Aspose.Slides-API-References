---
title: IChartCategoryCollection
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: コレクションを表します
type: docs
url: /ja/com.aspose.slides/ichartcategorycollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

[IChartCategory](../../com.aspose.slides/ichartcategory) のコレクションを表します
## メソッド

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getUseCells()](#getUseCells--) | true の場合、ワークシートがカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | true の場合、ワークシートがカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 使用されているカテゴリのグループ化レベルの数を返します。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | コレクションにカテゴリが存在する場合、それを返します。 |
| [add(Object value)](#add-java.lang.Object-) | 値から新しい [IChartCategory](../../com.aspose.slides/ichartcategory) を作成し、コレクションに追加します。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 指定された [IChartCategory](../../com.aspose.slides/ichartcategory) を検索し、コレクション全体での最初の出現のゼロベースインデックスを返します。 |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 指定された値を削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの要素を削除します。 |
| [clear()](#clear--) | コレクションのすべての要素を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 指定されたインデックスの要素。

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

true の場合、ワークシートがカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。false の場合、ワークシートは値の保存に使用されません（この場合は多層カテゴリをサポートしません）。読み書き可能なブール値。

**戻り値:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

true の場合、ワークシートがカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。false の場合、ワークシートは値の保存に使用されません（この場合は多層カテゴリをサポートしません）。読み書き可能なブール値。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

使用されているカテゴリのグループ化レベルの数を返します。マルチレベルカテゴリの場合は 1 より大きくなります。読み取り専用の整数。

**戻り値:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

コレクションにカテゴリが存在する場合、それを返します。存在しない場合、[IChartDataCell](../../com.aspose.slides/ichartdatacell) から新しいチャートカテゴリを作成し、コレクションに追加します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | チャートカテゴリの作成に使用されるセル。 |

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 追加されたまたは既存のカテゴリ。

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

値から新しい [IChartCategory](../../com.aspose.slides/ichartcategory) を作成し、コレクションに追加します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | 値。

--------------------

このメソッドは AUTO_DATA という名前のワークシートを追加し、すべての値をそこに追加します。[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないようにしてください。このメソッドで追加できる最大の値の数は 16711680 を超えてはなりません。|

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 追加された [IChartCategory](../../com.aspose.slides/ichartcategory)。

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

指定された [IChartCategory](../../com.aspose.slides/ichartcategory) を検索し、コレクション全体での最初の出現のゼロベースインデックスを返します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | チャートカテゴリ。 |

**戻り値:**
int - 値がコレクション全体で最初に出現したゼロベースインデックス（見つかった場合）。見つからない場合は -1。

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

指定された値を削除します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 値。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスの要素を削除します。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 削除するカテゴリのインデックス。

### clear() {#clear--}
```
public abstract void clear()
```

コレクションのすべての要素を削除します。