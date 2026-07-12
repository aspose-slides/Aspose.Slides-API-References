---
title: IPresentationHeaderFooterManager
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションのすべてのフッター、日付と時刻、ページ番号プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/ipresentationheaderfootermanager/
---
**実装されているすべてのインターフェース:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

プレゼンテーションのフッター、日付と時刻、ページ番号プレースホルダーのすべての動作を保持するマネージャーを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | ヘッダー プレースホルダーの表示状態を変更します（notes master、notes slides、handout master を含む）。 |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | フッター プレースホルダーの表示状態を変更します（master slides、layout slides、slides を含む）。 |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | ページ番号 プレースホルダーの表示状態を変更します（master slides、layout slides、slides を含む）。 |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | 日付と時刻 プレースホルダーの表示状態を変更します（master slides、layout slides、slides を含む）。 |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | ヘッダー プレースホルダーすべてにテキストを設定します（notes master、notes slides、handout master を含む）。 |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | フッター プレースホルダーすべてにテキストを設定します（master slides、layout slides、slides を含む）。 |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | 日付と時刻 プレースホルダーすべてにテキストを設定します（master slides、layout slides、slides を含む）。 |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | すべてのタイトル スライドおよび最初のレイアウト スライドに対して、フッター、日付と時刻、ページ番号プレースホルダーの表示状態を変更します。 |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```


ヘッダー プレースホルダーの表示状態を変更します（notes master、notes slides、handout master を含む）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダー プレースホルダーを表示にし、それ以外は非表示にします。 |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```


フッター プレースホルダーの表示状態を変更します（master slides、layout slides、slides を含む）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッター プレースホルダーを表示にし、それ以外は非表示にします。 |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```


ページ番号 プレースホルダーの表示状態を変更します（master slides、layout slides、slides を含む）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号 プレースホルダーを表示にし、それ以外は非表示にします。 |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```


日付と時刻 プレースホルダーの表示状態を変更します（master slides、layout slides、slides を含む）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付と時刻 プレースホルダーを表示にし、それ以外は非表示にします。 |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```


ヘッダー プレースホルダーすべてにテキストを設定します（notes master、notes slides、handout master を含む）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```


フッター プレースホルダーすべてにテキストを設定します（master slides、layout slides、slides を含む）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```


日付と時刻 プレースホルダーすべてにテキストを設定します（master slides、layout slides、slides を含む）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```


フッター、日付と時刻、ページ番号プレースホルダーの表示状態をすべてのタイトル スライドおよび最初のレイアウト スライドに対して変更します。タイトル スライド – 最初のレイアウト スライドに基づくスライド（この最初のレイアウトの種類に関係なく）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - プレースホルダーを表示にし、それ以外は非表示にします。 |