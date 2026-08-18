---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Represents a font definition.
type: docs
url: /ja/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Represents a font definition.
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFontName()](#getFontName--) | フォント名を返します。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | テーマ参照を実際に使用されるフォントに置き換えてフォント名を返します。 |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

フォント名を返します。 読み取り専用 String。

**戻り値:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

テーマ参照を実際に使用されるフォントに置き換えてフォント名を返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | テーマ化されたフォント名を取得するテーマ。呼び出し側が正しい値を提供する必要があります。 |

**戻り値:**
java.lang.String - フォント名。