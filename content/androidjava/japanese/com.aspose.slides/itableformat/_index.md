---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table.
type: docs
url: /ja/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

テーブルのフォーマットを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | テーブルの塗りつぶしプロパティオブジェクトを返します。 |
| [getTransparency()](#getTransparency--) | 塗りつぶし色の透明度を取得または設定します。 |
| [setTransparency(float value)](#setTransparency-float-) | 塗りつぶし色の透明度を取得または設定します。 |
| [getEffective()](#getEffective--) | 継承とテーブルスタイルが適用された有効なテーブル書式プロパティを取得します。 |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

テーブルの塗りつぶしプロパティオブジェクトを返します。 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

塗りつぶし色の透明度を取得または設定します。 読み取り/書き込み  float 。

**戻り値:**
float

### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

塗りつぶし色の透明度を取得または設定します。 読み取り/書き込み  float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

継承とテーブルスタイルが適用された有効なテーブル書式プロパティを取得します。

**戻り値:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata)。