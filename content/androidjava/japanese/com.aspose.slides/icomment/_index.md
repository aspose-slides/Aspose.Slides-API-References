---  
title: IComment  
second_title: Aspose.Slides for Android via Java API Reference  
description: Represents a comment on a slide.  
type: docs  
url: /ja/com.aspose.slides/icomment/  
---```
public interface IComment
```

スライド上のコメントを表します。  
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getText()](#getText--) | スライドコメントのプレーンテキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | スライドコメントのプレーンテキストを取得または設定します。 |
| [getCreatedTime()](#getCreatedTime--) | コメント作成時刻を取得または設定します。 |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | コメント作成時刻を取得または設定します。 |
| [getSlide()](#getSlide--) | コメントの親スライドを取得または設定します。 |
| [getAuthor()](#getAuthor--) | コメントの作成者を取得します。 |
| [getPosition()](#getPosition--) | スライド上のコメントの位置を取得または設定します。 |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | スライド上のコメントの位置を取得または設定します。 |
| [remove()](#remove--) | コメントとそのすべての返信を親コレクションから削除します。 |
| [getParentComment()](#getParentComment--) | 親コメントを取得または設定します。 |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | 親コメントを取得または設定します。 |
### getText() {#getText--}
```
public abstract String getText()
```

スライドコメントのプレーンテキストを取得または設定します。 読み取り/書き込み String.

**戻り値:**  
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

スライドコメントのプレーンテキストを取得または設定します。 読み取り/書き込み String.

**パラメーター:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

コメント作成時刻を取得または設定します。このプロパティを java.util.Date(Long.MIN_VALUE) に設定すると、コメント時刻が設定されていないことを意味します。 読み取り/書き込み java.util.Date.

--------------------

コメント時刻はオプションのパラメーターです。

**戻り値:**  
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

コメント作成時刻を取得または設定します。このプロパティを java.util.Date(Long.MIN_VALUE) に設定すると、コメント時刻が設定されていないことを意味します。 読み取り/書き込み java.util.Date.

--------------------

コメント時刻はオプションのパラメーターです。

**パラメーター:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

コメントの親スライドを取得または設定します。 読み取り専用 [ISlide](../../com.aspose.slides/islide).

**戻り値:**  
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

コメントの作成者を取得します。 読み取り専用 [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**戻り値:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

スライド上のコメントの位置を取得または設定します。 読み取り/書き込み android.graphics.PointF.

**戻り値:**  
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

スライド上のコメントの位置を取得または設定します。 読み取り/書き込み android.graphics.PointF.

**パラメーター:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

コメントとそのすべての返信を親コレクションから削除します。

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

親コメントを取得または設定します。 読み取り/書き込み [IComment](../../com.aspose.slides/icomment).

**戻り値:**  
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

親コメントを取得または設定します。 読み取り/書き込み [IComment](../../com.aspose.slides/icomment).

**パラメーター:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |