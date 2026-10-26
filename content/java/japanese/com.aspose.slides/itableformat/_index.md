---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: テーブルの形式を表します。
type: docs
url: /ja/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

テーブルの形式を表します。
## メソッド

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | テーブルの塗りつぶしプロパティオブジェクトを返します。 |
| [getTransparency()](#getTransparency--) | 塗りつぶし色の透明度を取得または設定します。 |
| [setTransparency(float value)](#setTransparency-float-) | 塗りつぶし色の透明度を取得または設定します。 |
| [getEffective()](#getEffective--) | 継承とテーブルスタイルが適用された有効なテーブル書式プロパティを取得します。 |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


テーブルの塗りつぶしプロパティオブジェクトを返します。 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat).

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


塗りつぶし色の透明度を取得または設定します。 読み書き  float .

**戻り値:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


塗りつぶし色の透明度を取得または設定します。 読み書き  float .

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


継承とテーブルスタイルが適用された有効なテーブル書式プロパティを取得します。

**戻り値:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).