---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides for Java API リファレンス
description: エクスポートされたドキュメントにおけるノートとコメントのレイアウトの外観を制御するオプションを提供します。
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

エクスポートされたドキュメントにおけるノートとコメントのレイアウトの外観を制御するオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | 既定のコンストラクタです。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | 著者がいないコメントの表示可否を取得または設定します。 |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | 著者がいないコメントの表示可否を取得または設定します。 |
| [getNotesPosition()](#getNotesPosition--) | ページ上のノートの位置を取得または設定します。 |
| [setNotesPosition(int value)](#setNotesPosition-int-) | ページ上のノートの位置を取得または設定します。 |
| [getCommentsPosition()](#getCommentsPosition--) | ページ上のコメントの位置を取得または設定します。 |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | ページ上のコメントの位置を取得または設定します。 |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | コメント領域の色を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。 |
| [setCommentsAreaColor(Color value)](#setCommentsAreaColor-java.awt.Color-) | コメント領域の色を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。 |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | コメント出力領域の幅（ピクセル単位）を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。 |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | コメント出力領域の幅（ピクセル単位）を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。 |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


既定のコンストラクタです。

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


著者がいないコメントの表示可否を取得または設定します。true の場合、コメントが表示されます。（コメントが表示されている場合にのみ適用されます）。

--------------------

デフォルト値は **false** です。

**戻り値:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


著者がいないコメントの表示可否を取得または設定します。true の場合、コメントが表示されます。（コメントが表示されている場合にのみ適用されます）。

--------------------

デフォルト値は **false** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


ページ上のノートの位置を取得または設定します。

--------------------

デフォルトは **NotesPositions.None** です。

**戻り値:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


ページ上のノートの位置を取得または設定します。

--------------------

デフォルトは **NotesPositions.None** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


ページ上のコメントの位置を取得または設定します。

--------------------

デフォルトは **CommentsPositions.None** です。

**戻り値:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


ページ上のコメントの位置を取得または設定します。

--------------------

デフォルトは **CommentsPositions.None** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Color getCommentsAreaColor()
```


コメント領域の色を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。

--------------------

デフォルトは **Color.SkyBlue** です。

**戻り値:**
java.awt.Color
### setCommentsAreaColor(Color value) {#setCommentsAreaColor-java.awt.Color-}
```
public final void setCommentsAreaColor(Color value)
```


コメント領域の色を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。

--------------------

デフォルトは **Color.SkyBlue** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


コメント出力領域の幅（ピクセル単位）を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。

--------------------

最小値およびデフォルト値は **150** です。

**戻り値:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


コメント出力領域の幅（ピクセル単位）を取得または設定します（コメントが右側に表示されている場合にのみ適用されます）。

--------------------

最小値およびデフォルト値は **150** です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |