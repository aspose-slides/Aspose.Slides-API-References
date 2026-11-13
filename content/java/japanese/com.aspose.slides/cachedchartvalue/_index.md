---
title: CachedChartValue
second_title: Aspose.Slides for Java API リファレンス
description: キャッシュされたチャート値（例：X Y バブルサイズまたはメイン値）を表します。
type: docs
url: /ja/com.aspose.slides/cachedchartvalue/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

キャッシュされたチャート値（例：X、Y、バブルサイズ、またはメイン値）を表します。

## コンストラクター

| コンストラクタ | 説明 |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [toString()](#toString--) | キャッシュされた値の文字列表現を返します。 |
| [toDouble()](#toDouble--) | キャッシュされた値を double に変換します。 |
| [getData()](#getData--) | キャッシュされたデータオブジェクトを取得します。 |

### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```

### toString() {#toString--}
```
public String toString()
```

キャッシュされた値の文字列表現を返します。

**戻り値:**
java.lang.String

### toDouble() {#toDouble--}
```
public final double toDouble()
```

キャッシュされた値を double に変換します。

**戻り値:**
double - 数値表現、または Data (\#getData.getData/\#setData(Object).setData(Object)) が null であるか double に変換できない場合は Double.NaN

### getData() {#getData--}
```
public final Object getData()
```

キャッシュされたデータオブジェクトを取得します。 読み取り専用 Object .

**戻り値:**
java.lang.Object