---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Java API リファレンス
description: レイアウトスライドのフッタ、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/layoutslideheaderfootermanager/
---
**継承:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**すべての実装インターフェイス:**  
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)  
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

レイアウトスライドのフッタ、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | レイアウトスライドのフッタプレースホルダーとすべての子フッタプレースホルダーの表示状態を変更します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | レイアウトスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | レイアウトスライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | レイアウトスライドのフッタプレースホルダーとすべての子フッタプレースホルダーにテキストを設定します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | レイアウトスライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

レイアウトスライドのフッタプレースホルダーとすべての子フッタプレースホルダーの表示状態を変更します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはマスタースライドを使用し、マスタースライドに依存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタプレースホルダーを表示し、false - それ以外の場合は非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

レイアウトスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示し、false - それ以外の場合は非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

レイアウトスライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻プレースホルダーを表示し、false - それ以外の場合は非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

レイアウトスライドのフッタプレースホルダーとすべての子フッタプレースホルダーにテキストを設定します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

レイアウトスライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |