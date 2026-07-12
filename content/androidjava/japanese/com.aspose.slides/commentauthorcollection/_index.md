---
title: CommentAuthorCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: コメント作成者のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/commentauthorcollection/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

コメント作成者のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [size()](#size--) | コレクションに実際に含まれる要素数を取得します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスにある要素を取得します。 |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | コレクションの末尾に新しい作成者を追加します。 |
| [toArray()](#toArray--) | すべての作成者を含む配列を作成し、返します。 |
| [findByName(String name)](#findByName-java.lang.String-) | 名前でコレクション内の作成者を検索します。 |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 名前とイニシャルでコレクション内の作成者を検索します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスにある作成者を削除します。 |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | コレクション内の指定された作成者の最初の出現を削除します。 |
| [clear()](#clear--) | コレクションからすべての作成者を削除します。 |
| [iterator()](#iterator--) | コレクションを列挙する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | コレクションのすべての要素を指定された配列にコピーします。 |
| [isSynchronized()](#isSynchronized--) | コレクションへのアクセスが同期 (スレッドセーフ) されているかどうかを示す値を返します。 |
| [getSyncRoot()](#getSyncRoot--) | 同期ルートを返します。 |
### size() {#size--}
```
public final int size()
```


コレクションに実際に含まれる要素数を取得します。読み取り専用 int。

**戻り値:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


指定されたインデックスにある要素を取得します。読み取り専用 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```


コレクションの末尾に新しい作成者を追加します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 新しい作成者の名前。 |
| initials | java.lang.String | 新しい作成者のイニシャル。 |

**戻り値:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 新しい [ICommentAuthor](../../com.aspose.slides/icommentauthor) オブジェクト。
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


すべての作成者を含む配列を作成し、返します。

**戻り値:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) の配列
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


名前でコレクション内の作成者を検索します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 検索対象の作成者の名前。 |

**戻り値:**
com.aspose.slides.ICommentAuthor[] - 作成者または null。
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


名前とイニシャルでコレクション内の作成者を検索します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 検索対象の作成者の名前。 |
| initials | java.lang.String | 検索対象の作成者のイニシャル。 |

**戻り値:**
com.aspose.slides.ICommentAuthor[] - 作成者または null。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


コレクションの指定されたインデックスにある作成者を削除します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


コレクション内の指定された作成者の最初の出現を削除します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | コレクションから削除する作成者。 |
### clear() {#clear--}
```
public final void clear()
```


コレクションからすべての作成者を削除します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


コレクションを列挙する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - コレクションを列挙するために使用できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - コレクション全体の java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


コレクションのすべての要素を指定された配列にコピーします。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | ターゲット配列。 |
| index | int | ターゲット配列の開始インデックス。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


コレクションへのアクセスが同期 (スレッドセーフ) されているかどうかを示す値を返します。読み取り専用 boolean。

**戻り値:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


同期ルートを返します。読み取り専用 Object。

**戻り値:**
java.lang.Object