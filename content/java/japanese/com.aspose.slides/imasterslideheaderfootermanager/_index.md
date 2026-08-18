---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides for Java API リファレンス
description: マスタースライドのフッター、日付時刻、ページ番号プレースホルダーとすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/imasterslideheaderfootermanager/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

マスタースライドのフッター、日付時刻、ページ番号プレースホルダーとすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーとは、依存レイアウトスライドや依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドやスライドはマスタースライドを使用し、依存します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | マスタースライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。子プレースホルダーとは、依存レイアウトスライドや依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドやスライドはマスタースライドを使用し、依存します。

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示します。それ以外の場合は非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

マスタースライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存レイアウトスライドや依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドやスライドはマスタースライドを使用し、依存します。

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示します。それ以外の場合は非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存レイアウトスライドや依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドやスライドはマスタースライドを使用し、依存します。

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻プレースホルダーを表示します。それ以外の場合は非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーとは、依存レイアウトスライドや依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドやスライドはマスタースライドを使用し、依存します。

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。子プレースホルダーとは、依存レイアウトスライドや依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドやスライドはマスタースライドを使用し、依存します。

**パラメータ:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |