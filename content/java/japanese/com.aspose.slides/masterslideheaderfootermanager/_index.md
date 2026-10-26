---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides for Java API リファレンス
description: マスタースライドのフッタ、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/masterslideheaderfootermanager/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

マスタースライドのフッタ、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーは、依存レイアウトスライドおよび依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドとスライドはマスタースライドを使用し、依存しています。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | マスタースライドのフッタプレースホルダーとすべての子フッタプレースホルダーの表示状態を変更します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | マスタースライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | マスタースライドのフッタプレースホルダーとすべての子フッタプレースホルダーにテキストを設定します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。 |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

マスタースライドのフッタプレースホルダーとすべての子フッタプレースホルダーの表示状態を変更します。子プレースホルダーは、依存レイアウトスライドおよび依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドとスライドはマスタースライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタプレースホルダーを表示にし、false - 非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

マスタースライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーは、依存レイアウトスライドおよび依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドとスライドはマスタースライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示にし、false - 非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。子プレースホルダーは、依存レイアウトスライドおよび依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドとスライドはマスタースライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻プレースホルダーを表示にし、false - 非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

マスタースライドのフッタプレースホルダーとすべての子フッタプレースホルダーにテキストを設定します。子プレースホルダーは、依存レイアウトスライドおよび依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドとスライドはマスタースライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。子プレースホルダーは、依存レイアウトスライドおよび依存スライドに含まれるプレースホルダーを意味します。依存レイアウトスライドとスライドはマスタースライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |