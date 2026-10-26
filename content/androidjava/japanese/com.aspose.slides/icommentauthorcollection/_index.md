---
title: ICommentAuthorCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: コメント作成者のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/icommentauthorcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

コメント作成者のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | コレクションの末尾に新しい作成者を追加します。 |
| [toArray()](#toArray--) | すべての作成者を含む配列を作成して返します。 |
| [findByName(String name)](#findByName-java.lang.String-) | 名前でコレクション内の作成者を検索します。 |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 名前とイニシャルでコレクション内の作成者を検索します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスにある作成者を削除します。 |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | コレクション内の指定された作成者の最初の出現を削除します。 |
| [clear()](#clear--) | コレクションからすべての作成者を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

コレクションの末尾に新しい作成者を追加します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 新しい作成者の名前。 |
| initials | java.lang.String | 新しい作成者のイニシャル。 |

**戻り値:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 新しい[ICommentAuthor](../../com.aspose.slides/icommentauthor)オブジェクト。
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

すべての作成者を含む配列を作成して返します。

**戻り値:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor)の配列。
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

名前でコレクション内の作成者を検索します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 検索する作成者の名前。 |

**戻り値:**
com.aspose.slides.ICommentAuthor[] - 作成者または null。
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

名前とイニシャルでコレクション内の作成者を検索します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | java.lang.String | 検索する作成者の名前。 |
| initials | java.lang.String | 検索する作成者のイニシャル。 |

**戻り値:**
com.aspose.slides.ICommentAuthor[] - 作成者または null。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションの指定されたインデックスにある作成者を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

コレクション内の指定された作成者の最初の出現を削除します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | コレクションから削除する作成者。 |
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての作成者を削除します。