---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: 含まれるハイパーリンクへの簡単なアクセスを提供します。
type: docs
url: /ja/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

含まれるハイパーリンクへの簡単なアクセスを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | null ではない HyperlinkClick を含むすべての IHyperlinkContainer サブオブジェクトを取得します。 |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | null ではない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクトを取得します。 |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | null ではない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクトを取得します。 |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | すべての IHyperlinkContainer サブオブジェクト内に含まれる HyperlinkClick と HyperlinkMouseOver のハイパーリンクをすべて削除します。 |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

null ではない HyperlinkClick を含むすべての IHyperlinkContainer サブオブジェクトを取得します。指定された IHyperlinkContainer オブジェクトでハイパーリンクを管理できます（読み取り、更新、または削除）。IHyperlinkContainer インターフェイスをご覧ください。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - null ではない HyperlinkClick を含むすべての IHyperlinkContainer サブオブジェクト
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

null ではない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクトを取得します。指定された IHyperlinkContainer オブジェクトでハイパーリンクを管理できます（読み取り、更新、または削除）。IHyperlinkContainer インターフェイスをご覧ください。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - null ではない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクト
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

null ではない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクトを取得します。指定された IHyperlinkContainer オブジェクトでハイパーリンクを管理できます（読み取り、更新、または削除）。IHyperlinkContainer インターフェイスをご覧ください。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - null ではない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクト
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

すべての IHyperlinkContainer サブオブジェクト内に含まれる HyperlinkClick と HyperlinkMouseOver のハイパーリンクをすべて削除します。