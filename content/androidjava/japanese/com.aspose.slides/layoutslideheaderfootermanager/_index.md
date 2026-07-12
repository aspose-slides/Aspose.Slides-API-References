---
title: LayoutSlideHeaderFooterManager
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: レイアウトスライドのフッター、日時、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/layoutslideheaderfootermanager/
---
**継承:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)  
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideFooterManager
```

レイアウトスライドのフッター、日時、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーとは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示を変更します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | レイアウトスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示を変更します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーの表示を変更します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示を変更します。子プレースホルダーとは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはマスタースライドを使用し、マスタースライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示にし、それ以外の場合は非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

レイアウトスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示を変更します。子プレースホルダーとは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示にし、それ以外の場合は非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーの表示を変更します。子プレースホルダーとは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日時プレースホルダーを表示にし、それ以外の場合は非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーとは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。子プレースホルダーとは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |