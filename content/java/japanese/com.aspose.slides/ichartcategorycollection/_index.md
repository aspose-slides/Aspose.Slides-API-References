---
title: IChartCategoryCollection
second_title: Aspose.Slides for Java API リファレンス
description: コレクションを表します
type: docs
url: /ja/com.aspose.slides/ichartcategorycollection/
---
**実装済みインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

[IChartCategory](../../com.aspose.slides/ichartcategory) のコレクションを表します。

## メソッド

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getUseCells()](#getUseCells--) | true の場合、ワークシートはカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | true の場合、ワークシートはカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 使用されているカテゴリのグループ化レベル数を返します。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | コレクションにカテゴリが存在すれば、それを返します。 |
| [add(Object value)](#add-java.lang.Object-) | 値から新しい [IChartCategory](../../com.aspose.slides/ichartcategory) を作成し、コレクションに追加します。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 指定された [IChartCategory](../../com.aspose.slides/ichartcategory) を検索し、コレクション全体で最初に出現する位置のゼロベースインデックスを返します。 |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 指定された値を削除します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスの要素を削除します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 指定されたインデックスの要素です。

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

true の場合、ワークシートはカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。false の場合、ワークシートは値の保存に使用されません（この場合は多層カテゴリをサポートしません）。読み書き可能な boolean。

**戻り値:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

true の場合、ワークシートはカテゴリの保存に使用されます（この場合は多層カテゴリをサポートします）。false の場合、ワークシートは値の保存に使用されません（この場合は多層カテゴリをサポートしません）。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

使用されているカテゴリのグループ化レベル数を返します。多層カテゴリの場合は 1 より大きくなります。読み取り専用の int。

**戻り値:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

コレクションにカテゴリが存在すればそれを返します。存在しない場合は [IChartDataCell](../../com.aspose.slides/ichartdatacell) から新しいチャートカテゴリを作成し、コレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | チャートカテゴリ作成に使用するセル。 |

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 追加されたカテゴリまたは既存のカテゴリ。

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

値から新しい [IChartCategory](../../com.aspose.slides/ichartcategory) を作成し、コレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object | 値。

--------------------

このメソッドは名前が AUTO_DATA のワークシートを追加し、すべての値をそこに追加します。[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないようにしてください。このメソッドで追加できる最大の値の数は 16711680 を超えてはいけません。

**戻り値:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 追加された [IChartCategory](../../com.aspose.slides/ichartcategory)。

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

指定された [IChartCategory](../../com.aspose.slides/ichartcategory) を検索し、コレクション全体で最初に出現する位置のゼロベースインデックスを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | チャートカテゴリ。 |

**戻り値:**
int - コレクション全体で最初に出現する値のゼロベースインデックス（見つからなければ -1）。

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

指定された値を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 値。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスの要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するカテゴリのインデックス。

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての要素を削除します。