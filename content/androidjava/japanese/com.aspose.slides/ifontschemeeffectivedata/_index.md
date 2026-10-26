---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API リファレンス
description: 効果的なフォントスキームのプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

効果的なフォントスキームのプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMinor()](#getMinor--) | スライドの「body」部分のフォントコレクションを返します。 |
| [getMajor()](#getMajor--) | スライドの「heading」部分のフォントコレクションを返します。 |
| [getName()](#getName--) | フォントスキーム名を返します。 |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

スライドの「body」部分のフォントコレクションを返します。読み取り専用 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)。

**戻り値:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

スライドの「heading」部分のフォントコレクションを返します。読み取り専用 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)。

**戻り値:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

フォントスキーム名を返します。読み取り専用 String.

**戻り値:**
java.lang.String