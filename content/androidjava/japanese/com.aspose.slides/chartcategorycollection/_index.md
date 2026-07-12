---
title: ChartCategoryCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: コレクションを表します
type: docs
url: /ja/com.aspose.slides/chartcategorycollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)  
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

[ChartCategory](../../com.aspose.slides/chartcategory) のコレクションを表します  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getUseCells()](#getUseCells--) | true の場合、ワークシートはカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | true の場合、ワークシートはカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 使用されるカテゴリ グループ化レベルの数を返します。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | コレクションにカテゴリが存在する場合、返します。 |
| [add(Object value)](#add-java.lang.Object-) | 値から新しい [ChartCategory](../../com.aspose.slides/chartcategory) を作成し、コレクションに追加します。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 指定された [ChartCategory](../../com.aspose.slides/chartcategory) を検索し、コレクション全体での最初の出現の 0 ベースインデックスを返します。 |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 指定された値を削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの要素を削除します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [iterator()](#iterator--) | コレクションを列挙するイテレータを返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [size()](#size--) | コレクション内の要素数を返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | リストへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | コレクションへのアクセスを同期化するために使用できるオブジェクトを返します。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 指定されたインデックスの要素です。

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

true の場合、ワークシートはカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。false の場合、ワークシートは値の保存に使用されません（この場合は多層カテゴリをサポートしません）。読み書き可能な boolean。

**戻り値:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

true の場合、ワークシートはカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。false の場合、ワークシートは値の保存に使用されません（この場合は多層カテゴリをサポートしません）。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

使用されるカテゴリ グループ化レベルの数を返します。マルチレベルカテゴリの場合は 1 より大きくなります。読み取り専用の int。

**戻り値:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

コレクションにカテゴリが存在する場合、返します。存在しない場合は [IChartDataCell](../../com.aspose.slides/ichartdatacell) から新しいチャートカテゴリを作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | チャートカテゴリ作成に使用されるセル。 |

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 追加されたまたは既存のカテゴリ。

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

値から新しい [ChartCategory](../../com.aspose.slides/chartcategory) を作成し、コレクションに追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object | 値。 |

--------------------

このメソッドは名前が AUTO_DATA のワークシートを追加し、すべての値をそこに追加します。[ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないようにしてください。このメソッドで追加できる最大値の数は 16711680 |  

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 追加された [IChartCategory](../../com.aspose.slides/ichartcategory)。

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

指定された [ChartCategory](../../com.aspose.slides/chartcategory) を検索し、コレクション全体での最初の出現の 0 ベースインデックスを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | チャートカテゴリ。 |

**戻り値:**
int - 値がコレクション全体で最初に出現した 0 ベースインデックス（見つからなければ -1）。

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

指定された値を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 値。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスの要素を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するカテゴリのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての要素を削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

コレクションを列挙するイテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - コレクションを列挙するために使用できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - コレクション全体の java.util.Iterator。

### size() {#size--}
```
public final int size()
```

コレクション内の要素数を返します。読み取り専用の int。

**戻り値:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 対象配列。 |
| index | int | 配列内の開始インデックス。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

リストへのアクセスが同期化されているか（スレッドセーフ）を示す値を返します。読み取り専用の boolean。

**戻り値:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

コレクションへのアクセスを同期化するために使用できるオブジェクトを返します。読み取り専用の Object。

同期化ルートを返します。読み取り専用の Object。

**戻り値:**
java.lang.Object