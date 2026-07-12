---
title: IParagraphCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 段落のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/iparagraphcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

段落のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [getCount()](#getCount--) | コレクションに実際に含まれる要素数を取得します。 |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Paragraph をコレクションの末尾に追加します。 |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | ParagraphCollection のコンテンツをコレクションの末尾に追加します。 |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | 指定されたインデックスに Paragraph をコレクションに挿入します。 |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | 指定されたインデックスに ParagraphCollection のコンテンツをコレクションに挿入します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクション内の指定されたインデックスの要素を削除します。 |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | 特定の段落の最初の出現を削除します。 |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | 指定された HTML 文字列からテキストをコレクションに追加します。 |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | 指定された HTML 文字列からテキストをコレクションに追加します。 |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | 指定された段落を HTML に変換し、String オブジェクトとして返します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


指定されたインデックスの要素を取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


Paragraph をコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 末尾に追加する Paragraph。 |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


ParagraphCollection のコンテンツをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 末尾に追加する ParagraphCollection。 |

**戻り値:**
int - Paragraph が追加されたインデックス、または追加するものがない場合は -1。

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


指定されたインデックスに Paragraph をコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | Paragraph を挿入する 0 ベースのインデックス。 |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | 挿入する Paragraph。 |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


指定されたインデックスに ParagraphCollection のコンテンツをコレクションに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 段落を挿入する 0 ベースのインデックス。 |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | 挿入する段落。 |

### clear() {#clear--}
```
public abstract void clear()
```


コレクションからすべての要素を削除します。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


コレクション内の指定されたインデックスの要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素の 0 ベースインデックス。 |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


特定の段落の最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | コレクションから削除する段落。 |

**戻り値:**
boolean - アイテムが正常に削除された場合は true、そうでない場合は false。

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


指定された HTML 文字列からテキストをコレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | HTML テキスト。 |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


指定された HTML 文字列からテキストをコレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | HTML テキスト。 |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI を解決し参照オブジェクトを取得するコールバックオブジェクト。 |
| uri | java.lang.String | HTML ドキュメントを追加するための URI。相対リンクの解決に使用します。

--------------------

リゾルバーを指定すると脆弱性が発生する可能性があります。注意して使用してください。 |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


指定された段落を HTML に変換し、String オブジェクトとして返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstParagraphIndex | int | 最初の段落インデックス |
| paragraphsCount | int | 段落数 |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | 変換オプション [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**戻り値:**
java.lang.String - 生成された HTML。