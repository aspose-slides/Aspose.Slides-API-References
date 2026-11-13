---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: キャッシュされたチャート値（例：X、Y、バブルサイズ、またはメイン値）を表します。
type: docs
url: /ja/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

キャッシュされたチャート値を表します（例: X、Y、バブルサイズ、またはメイン値）。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getData()](#getData--) | キャッシュされたデータ オブジェクトを取得します。 |
| [toDouble()](#toDouble--) | キャッシュされた値を double に変換します。 |
### getData() {#getData--}
```
public abstract Object getData()
```


キャッシュされたデータ オブジェクトを取得します。読み取り専用  Object .

**戻り値:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


キャッシュされた値を double に変換します。

**戻り値:**
double - 数値表現、または Data (#getData.getData) が null または double に変換できない場合は Double.NaN。