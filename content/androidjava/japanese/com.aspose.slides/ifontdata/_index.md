---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: フォント定義を表します。
type: docs
url: /ja/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

フォント定義を表します。
## メソッド

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | フォント名を返します。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | フォント名を返します。テーマ参照を実際に使用されるフォントに置き換えます。 |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


フォント名を返します。読み取り専用 String.

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


フォント名を返します。テーマ参照を実際に使用されるフォントに置き換えます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | テーマ化されたフォント名を取得する元となるテーマです。正しい値を提供するのは呼び出し側の責任です。 |

**Returns:**
java.lang.String - フォント名。