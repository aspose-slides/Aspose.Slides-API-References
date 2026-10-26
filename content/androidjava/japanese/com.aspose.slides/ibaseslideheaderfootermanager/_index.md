---
title: IBaseSlideHeaderFooterManager
second_title: Java API リファレンスを使用した Android 用 Aspose.Slides
description: すべてのスライドタイプに対して、フッター、日付時刻、ページ番号プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/ibaseslideheaderfootermanager/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

すべてのスライドタイプに対してフッター、日付時刻、ページ番号プレースホルダーの動作を保持するマネージャーを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | フッタープレースホルダーが存在することを示す値を取得します。ブール値を読み取ります。 |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | ページ番号プレースホルダーが存在することを示す値を取得します。ブール値を読み取ります。 |
| [isDateTimeVisible()](#isDateTimeVisible--) | 日付時刻プレースホルダーが存在することを示す値を取得します。ブール値を読み取ります。 |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | スライドのフッタープレースホルダーの表示状態を変更します。 |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | スライドのページ番号プレースホルダーの表示状態を変更します。 |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | スライドの日付時刻プレースホルダーの表示状態を変更します。 |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | スライドのフッタープレースホルダーにテキストを設定します。 |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | スライドの日付時刻プレースホルダーにテキストを設定します。 |

### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

フッタープレースホルダーが存在することを示す値を取得します。ブール値を読み取ります。

**戻り値:**
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

ページ番号プレースホルダーが存在することを示す値を取得します。ブール値を読み取ります。

**戻り値:**
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

日付時刻プレースホルダーが存在することを示す値を取得します。ブール値を読み取ります。

**戻り値:**
boolean

### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

スライドのフッタープレースホルダーの表示状態を変更します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示にし、false - 非表示にします。 |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

スライドのページ番号プレースホルダーの表示状態を変更します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示にし、false - 非表示にします。 |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

スライドの日付時刻プレースホルダーの表示状態を変更します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻プレースホルダーを表示にし、false - 非表示にします。 |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

スライドのフッタープレースホルダーにテキストを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

スライドの日付時刻プレースホルダーにテキストを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |