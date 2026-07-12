---
title: ColorOperation
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 色変換に使用されるさまざまなカラー操作を表します。
type: docs
url: /ja/com.aspose.slides/coloroperation/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

色変換で使用されるさまざまなカラー操作を表します。変更不可能なオブジェクトです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | 新しいカラー変換操作を作成します。 |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | 新しいカラー変換操作を作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOperationType()](#getOperationType--) | 操作のタイプを取得または設定します。 |
| [getParameter()](#getParameter--) | 操作のパラメータを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 二つの ColorOperation インスタンスが等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルなどのデータ構造での使用に適しています。 |

### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

新しいカラー変換操作を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| op | int | 操作タイプ。 |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

新しいカラー変換操作を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| op | int | 操作タイプ。 |
| parameter | float | 操作パラメータ。 |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

操作のタイプを取得または設定します。読み取り専用 [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)。

**戻り値:**
int

### getParameter() {#getParameter--}
```
public final float getParameter()
```

操作のパラメータを取得します。読み取り専用 float。

**戻り値:**
float

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

二つの ColorOperation インスタンスが等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 現在の ColorOperation と比較する ColorOperation。 |

**戻り値:**
boolean - **true** 指定された ColorOperation が現在の ColorOperation と等しい場合; それ以外の場合は **false**。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルなどのデータ構造での使用に適しています。

**戻り値:**
int