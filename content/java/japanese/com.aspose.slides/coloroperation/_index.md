---
title: ColorOperation
second_title: Aspose.Slides for Java API リファレンス
description: 色変換に使用されるさまざまなカラー操作を表します。
type: docs
url: /ja/com.aspose.slides/coloroperation/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)  
```
public class ColorOperation implements IColorOperation
```

色変換に使用されるさまざまなカラー操作を表します。不変オブジェクト。

## Constructors

| Constructor | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | 新しいカラー変換操作を作成します。 |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | 新しいカラー変換操作を作成します。 |

## Methods

| Method | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | 操作のタイプを取得または設定します。 |
| [getParameter()](#getParameter--) | 操作のパラメータを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 2つの ColorOperation インスタンスが等しいかどうかを判定します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルなどのデータ構造での使用に適しています。 |

### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

新しいカラー変換操作を作成します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | 操作タイプ。 |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

新しいカラー変換操作を作成します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | 操作タイプ。 |
| parameter | float | 操作パラメータ。 |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

操作のタイプを取得または設定します。読み取り専用 [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)。

**Returns:**  
int

### getParameter() {#getParameter--}
```
public final float getParameter()
```

操作のパラメータを取得します。読み取り専用 float。

**Returns:**  
float

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

2つの ColorOperation インスタンスが等しいかどうかを判定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 現在の ColorOperation と比較する ColorOperation。 |

**Returns:**  
boolean - **true** if the specified ColorOperation is equal to the current ColorOperation; otherwise, **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルなどのデータ構造での使用に適しています。

**Returns:**  
int