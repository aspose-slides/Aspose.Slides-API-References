---
title: IFontSubstRule
second_title: Aspose.Slides for Android の Java API リファレンス
description: フォント置換情報を表します
type: docs
url: /ja/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

フォント置換情報を表します
## メソッド

| Method | Description |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 置換対象フォント 読み取り専用 [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | 置換に使用するフォント 読み取り専用 [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 置換に適用するルール 読み取り専用 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```

置換対象フォント 読み取り専用 [IFontData](../../com.aspose.slides/ifontdata).

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```

置換に使用するフォント 読み取り専用 [IFontData](../../com.aspose.slides/ifontdata).

**戻り値:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```

置換に適用するルール 読み取り専用 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**戻り値:**
int