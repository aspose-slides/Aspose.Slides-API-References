---
title: IOverrideTheme
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: オーバーライドテーマを表します。
type: docs
url: /ja/com.aspose.slides/ioverridetheme/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

オーバーライドテーマを表します。
## メソッド

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | True 値は、ColorScheme、FontScheme、FormatScheme が null であり、このテーマオブジェクトでのオーバーライドが無効になっていることを意味します。 |
| [initColorScheme()](#initColorScheme--) | InheritedTheme の ColorScheme をオーバーライドするために、新しいオブジェクトで ColorScheme を初期化します。 |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | InheritedTheme の ColorScheme をオーバーライドするために、新しいオブジェクトで ColorScheme を初期化します。 |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | InheritedTheme の ColorScheme をオーバーライドするために、新しいオブジェクトで ColorScheme を初期化します。 |
| [initFontScheme()](#initFontScheme--) | InheritedTheme の FontScheme をオーバーライドするために、新しいオブジェクトで FontScheme を初期化します。 |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | InheritedTheme の FontScheme をオーバーライドするために、新しいオブジェクトで FontScheme を初期化します。 |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | InheritedTheme の FontScheme をオーバーライドするために、新しいオブジェクトで FontScheme を初期化します。 |
| [initFormatScheme()](#initFormatScheme--) | InheritedTheme の FormatScheme をオーバーライドするために、新しいオブジェクトで FormatScheme を初期化します。 |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | InheritedTheme の FormatScheme をオーバーライドするために、新しいオブジェクトで FormatScheme を初期化します。 |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | InheritedTheme の FormatScheme をオーバーライドするために、新しいオブジェクトで FormatScheme を初期化します。 |
| [clear()](#clear--) | ColorScheme、FontScheme、FormatScheme を null に設定し、このテーマオブジェクトでのオーバーライドを無効化します。 |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

True 値は、ColorScheme、FontScheme、FormatScheme が null であり、このテーマオブジェクトでのオーバーライドが無効になっていることを意味します。読み取り専用 boolean。

**戻り値:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

InheritedTheme の ColorScheme をオーバーライドするために、新しいオブジェクトで ColorScheme を初期化します。
### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

InheritedTheme の ColorScheme をオーバーライドするために、新しいオブジェクトで ColorScheme を初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | 初期化に使用するデータ。 |
### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

InheritedTheme の ColorScheme をオーバーライドするために、新しいオブジェクトで ColorScheme を初期化し、この新しいオブジェクトのデータを InheritedTheme の ColorScheme のデータで初期化します。
### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

InheritedTheme の FontScheme をオーバーライドするために、新しいオブジェクトで FontScheme を初期化します。
### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

InheritedTheme の FontScheme をオーバーライドするために、新しいオブジェクトで FontScheme を初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | 初期化に使用するデータ。 |
### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

InheritedTheme の FontScheme をオーバーライドするために、新しいオブジェクトで FontScheme を初期化し、この新しいオブジェクトのデータを InheritedTheme の FontScheme のデータで初期化します。
### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

InheritedTheme の FormatScheme をオーバーライドするために、新しいオブジェクトで FormatScheme を初期化します。
### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

InheritedTheme の FormatScheme をオーバーライドするために、新しいオブジェクトで FormatScheme を初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | 初期化に使用するデータ。 |
### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

InheritedTheme の FormatScheme をオーバーライドするために、新しいオブジェクトで FormatScheme を初期化し、この新しいオブジェクトのデータを InheritedTheme の FormatScheme のデータで初期化します。
### clear() {#clear--}
```
public abstract void clear()
```

ColorScheme、FontScheme、FormatScheme を null に設定し、このテーマオブジェクトでのオーバーライドを無効化します。