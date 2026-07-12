---
title: BaseSlideHeaderFooterManager
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: すべてのスライドタイプに対して、フッター、日付時刻、ページ番号プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/baseslideheaderfootermanager/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

すべてのスライドタイプに対してフッター、日付時刻、ページ番号プレースホルダーの動作を保持するマネージャーを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | フッタープレースホルダーが存在することを示す値を取得します。boolean を読み取ります。 |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | ページ番号プレースホルダーが存在することを示す値を取得します。boolean を読み取ります。 |
| [isDateTimeVisible()](#isDateTimeVisible--) | 日付時刻プレースホルダーが存在することを示す値を取得します。boolean を読み取ります。 |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | スライドのフッタープレースホルダーの表示状態を変更します。 |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | スライドのページ番号プレースホルダーの表示状態を変更します。 |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | スライドの日付時刻プレースホルダーの表示状態を変更します。 |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | スライドのフッタープレースホルダーにテキストを設定します。 |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | スライドの日付時刻プレースホルダーにテキストを設定します。 |

### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

フッタープレースホルダーが存在することを示す値を取得します。boolean を読み取ります。

**戻り値:**
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

ページ番号プレースホルダーが存在することを示す値を取得します。boolean を読み取ります。

**戻り値:**
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

日付時刻プレースホルダーが存在することを示す値を取得します。boolean を読み取ります。

**戻り値:**
boolean

### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

スライドのフッタープレースホルダーの表示状態を変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示し、false - 非表示にします。 |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

スライドのページ番号プレースホルダーの表示状態を変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示し、false - 非表示にします。 |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

スライドの日付時刻プレースホルダーの表示状態を変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻プレースホルダーを表示し、false - 非表示にします。 |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

スライドのフッタープレースホルダーにテキストを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

スライドの日付時刻プレースホルダーにテキストを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |