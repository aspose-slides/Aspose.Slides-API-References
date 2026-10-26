---
title: NotesCommentsLayoutingOptions
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: エクスポートされたドキュメント内のノートとコメントのレイアウト外観を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/notescommentslayoutingoptions/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

エクスポートされたドキュメント内のノートとコメントのレイアウトの外観を制御するオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | デフォルトコンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | 著者が設定されていないコメントの表示可否を取得または設定します。 |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | 著者が設定されていないコメントの表示可否を取得または設定します。 |
| [getNotesPosition()](#getNotesPosition--) | ページ上のノートの位置を取得または設定します。 |
| [setNotesPosition(int value)](#setNotesPosition-int-) | ページ上のノートの位置を取得または設定します。 |
| [getCommentsPosition()](#getCommentsPosition--) | ページ上のコメントの位置を取得または設定します。 |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | ページ上のコメントの位置を取得または設定します。 |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | コメント領域の色を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。 |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | コメント領域の色を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。 |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | コメント出力領域の幅（ピクセル単位）を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。 |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | コメント出力領域の幅（ピクセル単位）を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。 |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


デフォルトコンストラクタ。

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


著者が設定されていないコメントの表示可否を取得または設定します。true の場合、コメントが表示されます（コメントが表示されている場合にのみ適用されます）。

--------------------

デフォルト値は **false**。

**戻り値:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


著者が設定されていないコメントの表示可否を取得または設定します。true の場合、コメントが表示されます（コメントが表示されている場合にのみ適用されます）。

--------------------

デフォルト値は **false**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


ページ上のノートの位置を取得または設定します。

--------------------

デフォルトは **NotesPositions.None**。

**戻り値:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


ページ上のノートの位置を取得または設定します。

--------------------

デフォルトは **NotesPositions.None**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


ページ上のコメントの位置を取得または設定します。

--------------------

デフォルトは **CommentsPositions.None**。

**戻り値:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


ページ上のコメントの位置を取得または設定します。

--------------------

デフォルトは **CommentsPositions.None**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```


コメント領域の色を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。

--------------------

デフォルトは **SkyBlue**。

**戻り値:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```


コメント領域の色を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。

--------------------

デフォルトは **SkyBlue**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


コメント出力領域の幅（ピクセル単位）を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。

--------------------

最小およびデフォルト値は **150**。

**戻り値:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


コメント出力領域の幅（ピクセル単位）を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。

--------------------

最小およびデフォルト値は **150**。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |