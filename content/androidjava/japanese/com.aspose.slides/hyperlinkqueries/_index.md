---
title: HyperlinkQueries
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 含まれるハイパーリンクへの簡単なアクセスを提供します。
type: docs
url: /ja/com.aspose.slides/hyperlinkqueries/
---
**継承:**
java.lang.Object

**すべての実装インターフェイス:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

含まれるハイパーリンクへの簡単なアクセスを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | null でない HyperlinkClick を含むすべての IHyperlinkContainer サブオブジェクトを取得します。 |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | null でない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクトを取得します。 |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | null でない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクトを取得します。 |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | すべての IHyperlinkContainer サブオブジェクトに含まれる HyperlinkClick と HyperlinkMouseOver のハイパーリンクをすべて削除します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

null でない HyperlinkClick を含むすべての IHyperlinkContainer サブオブジェクトを取得します。指定された IHyperlinkContainer オブジェクトでハイパーリンクを管理できます（読み取り、更新、削除）。IHyperlinkContainer インターフェイスを参照してください。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

null でない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクトを取得します。指定された IHyperlinkContainer オブジェクトでハイパーリンクを管理できます（読み取り、更新、削除）。IHyperlinkContainer インターフェイスを参照してください。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

null でない HyperlinkMouseOver を含むすべての IHyperlinkContainer サブオブジェクトを取得します。指定された IHyperlinkContainer オブジェクトでハイパーリンクを管理できます（読み取り、更新、削除）。IHyperlinkContainer インターフェイスを参照してください。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

すべての IHyperlinkContainer サブオブジェクトに含まれる HyperlinkClick と HyperlinkMouseOver のハイパーリンクをすべて削除します。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent\_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject