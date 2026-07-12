---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an author of comments.
type: docs
url: /ja/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

コメントの著者を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | 著者の名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 著者の名前を取得または設定します。 |
| [getInitials()](#getInitials--) | 著者のイニシャルを取得または設定します。 |
| [setInitials(String value)](#setInitials-java.lang.String-) | 著者のイニシャルを取得または設定します。 |
| [getComments()](#getComments--) | この著者が作成したコメントのコレクションを返します。 |
| [remove()](#remove--) | 親コレクションから著者を削除します。 |
### getName() {#getName--}
```
public abstract String getName()
```


著者の名前を取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


著者の名前を取得または設定します。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


著者のイニシャルを取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


著者のイニシャルを取得または設定します。読み書き可能 String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


この著者が作成したコメントのコレクションを返します。読み取り専用 [ICommentCollection](../../com.aspose.slides/icommentcollection)。

**戻り値:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


親コレクションから著者を削除します。