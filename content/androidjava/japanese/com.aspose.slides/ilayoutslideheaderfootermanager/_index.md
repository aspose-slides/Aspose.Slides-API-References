---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Android の Java API リファレンス
description: レイアウトスライドのフッター、日時、ページ番号プレースホルダーとすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

レイアウトスライドのフッター、日時、ページ番号プレースホルダーとすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはマスター スライドを使用し、マスター スライドに依存します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | レイアウトスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはマスター スライドを使用し、マスター スライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示し、それ以外は非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

レイアウトスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示し、それ以外は非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日時プレースホルダーを表示し、それ以外は非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。子プレースホルダーとは、依存スライド上に含まれるプレースホルダーを意味します。依存スライドはレイアウトスライドを使用し、レイアウトスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |