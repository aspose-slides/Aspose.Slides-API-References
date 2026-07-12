---
title: IPortionFormatEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 実効テキスト部分の書式設定プロパティを含む不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/iportionformateffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

実効テキスト部分の書式設定プロパティを含む不変オブジェクト。

--------------------

このインターフェイスは [IPortionFormat](../../com.aspose.slides/iportionformat) インターフェイスと共に使用され、継承が適用された実効書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | ブックマーク識別子を返します。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | マウスクリック用に定義されたハイパーリンクを返します。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | マウスオーバー用に定義されたハイパーリンクを返します。 |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

ブックマーク識別子を返します。 読み取り専用 String。

**戻り値:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

マウスクリック用に定義されたハイパーリンクを返します。 読み取り専用 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

マウスオーバー用に定義されたハイパーリンクを返します。 読み取り専用 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)