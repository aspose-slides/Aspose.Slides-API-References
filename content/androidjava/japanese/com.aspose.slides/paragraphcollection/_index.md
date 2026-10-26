---
title: ParagraphCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: 段落のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/paragraphcollection/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)  
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

段落のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Paragraph をコレクションの末尾に追加します。 |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | ParagraphCollection の内容をコレクションの末尾に追加します。 |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | List 内の特定の項目のインデックスを決定します。 |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 指定されたインデックスに Paragraph をコレクションに挿入します。 |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 指定されたインデックスに ParagraphCollection の内容をコレクションに挿入します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) に特定の値が含まれているかどうかを判断します。 |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を特定の配列インデックスから配列にコピーします。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスの要素を削除します。 |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。 |
| [iterator()](#iterator--) | コレクションを列挙する enumerator を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java iterator を返します。 |
| [getSlide()](#getSlide--) | 段落コレクションの親スライドを返します。 |
| [getPresentation()](#getPresentation--) | 段落コレクションの親プレゼンテーションを返します。 |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 指定された HTML 文字列からテキストをコレクションに追加します。 |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 指定された HTML 文字列からテキストをコレクションに追加します。 |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 指定された段落を HTML に変換し、String オブジェクトとして返します。 |
### getCount() {#getCount--}
```
public final int getCount()
```

コレクションに実際に含まれる要素数を取得します。読み取り専用 int.

**戻り値:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。読み取り専用 boolean.

**戻り値:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Paragraph をコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | コレクションの末尾に追加される Paragraph。 |
### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

ParagraphCollection の内容をコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | コレクションの末尾に追加される ParagraphCollection。 |

**戻り値:**
int - Paragraph が追加されたインデックス、または追加するものがない場合は -1。
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

List 内の特定の項目のインデックスを決定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | List 内で検索するオブジェクト。 |

**戻り値:**
int - アイテムがリスト内に見つかった場合のインデックス、見つからない場合は -1。
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

指定されたインデックスに Paragraph をコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Paragraph を挿入すべきゼロベースインデックス。 |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 挿入する Paragraph。 |
### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

指定されたインデックスに ParagraphCollection の内容をコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 段落を挿入すべきゼロベースインデックス。 |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 挿入する段落。 |
### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての要素を削除します。
### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するオブジェクト。 |

**戻り値:**
boolean - アイテムが [IGenericCollection](../../com.aspose.slides/igenericcollection) に見つかった場合は true、そうでない場合は false。
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を特定の配列インデックスから配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からコピーされた要素の宛先となる一次元配列。配列はゼロベースインデックスです。 |
| arrayIndex | int | コピー開始位置の配列インデックス（ゼロベース）。 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションの指定されたインデックスの要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |
### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から削除するオブジェクト。 |

**戻り値:**
boolean - アイテムが [IGenericCollection](../../com.aspose.slides/igenericcollection) から正常に削除された場合は true、そうでない場合は false。アイテムが元の [IGenericCollection](../../com.aspose.slides/igenericcollection) に見つからない場合も false を返します。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

コレクションを列挙する enumerator を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - コレクションを列挙するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

コレクション全体の java iterator を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - コレクション全体の java.util.Iterator。
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

段落コレクションの親スライドを返します。読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

段落コレクションの親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

指定された HTML 文字列からテキストをコレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | HTML テキスト。 |
### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

指定された HTML 文字列からテキストをコレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | HTML テキスト。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI を解決し、参照オブジェクトを取得するコールバックオブジェクト。 |
| uri | java.lang.String | HTML ドキュメントを追加するための URI。相対リンクの解決に使用されます。

--------------------

リゾルバを指定すると脆弱性が生じる可能性があります。注意して使用してください。 |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

指定された段落を HTML に変換し、String オブジェクトとして返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstParagraphIndex | int | 最初の段落インデックス (int) |
| paragraphsCount | int | 段落数 (int) |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Convert options [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**戻り値:**
java.lang.String - 生成された HTML。