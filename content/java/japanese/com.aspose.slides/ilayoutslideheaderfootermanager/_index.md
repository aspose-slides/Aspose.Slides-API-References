---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Java API リファレンス
description: レイアウト スライドのフッター、日時、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

レイアウト スライドのフッター、日時、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウト スライドを使用し、レイアウト スライドに依存します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | レイアウト スライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | レイアウト スライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | レイアウト スライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | レイアウト スライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | レイアウト スライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

レイアウト スライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはマスタースライドを使用し、マスタースライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示し、そうでない場合は非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

レイアウト スライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウト スライドを使用し、レイアウト スライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示し、そうでない場合は非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

レイアウト スライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウト スライドを使用し、レイアウト スライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻プレースホルダーを表示し、そうでない場合は非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

レイアウト スライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウト スライドを使用し、レイアウト スライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

レイアウト スライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。依存スライドはレイアウト スライドを使用し、レイアウト スライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |