---
title: CommentAuthor
second_title: Aspose.Slides for Java API リファレンス
description: コメントの作成者を表します。
type: docs
url: /ja/com.aspose.slides/commentauthor/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ICommentAuthor](../../com.aspose.slides/icommentauthor), com.aspose.slides.IDOMObject
```
public final class CommentAuthor implements ICommentAuthor, IDOMObject
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
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getName() {#getName--}
```
public final String getName()
```

作者の名前を取得または設定します。 読み書き可能 String.

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

作者の名前を取得または設定します。 読み書き可能 String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public final String getInitials()
```

作者のイニシャルを取得または設定します。 読み書き可能 String.

**戻り値:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public final void setInitials(String value)
```

作者のイニシャルを取得または設定します。 読み書き可能 String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final ICommentCollection getComments()
```

この作者が作成したコメントのコレクションを取得します。 読み取り専用 [ICommentCollection](../../com.aspose.slides/icommentcollection).

**戻り値:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public final void remove()
```

親コレクションから作者を削除します。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを取得します。 読み取り専用 IDOMObject.

**戻り値:**
com.aspose.slides.IDOMObject