---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: Represents an author of comments.
type: docs
url: /ja/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

コメントの作成者を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | 作者の名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 作者の名前を取得または設定します。 |
| [getInitials()](#getInitials--) | 作者のイニシャルを取得または設定します。 |
| [setInitials(String value)](#setInitials-java.lang.String-) | 作者のイニシャルを取得または設定します。 |
| [getComments()](#getComments--) | この作者が作成したコメントのコレクションを取得します。 |
| [remove()](#remove--) | 親コレクションから作者を削除します。 |
### getName() {#getName--}
```
public abstract String getName()
```

作者の名前を取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

作者の名前を取得または設定します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

作者のイニシャルを取得または設定します。読み書き可能 String。

**戻り値:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

作者のイニシャルを取得または設定します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

この作者が作成したコメントのコレクションを取得します。読み取り専用 [ICommentCollection](../../com.aspose.slides/icommentcollection)。

**戻り値:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

親コレクションから作者を削除します。