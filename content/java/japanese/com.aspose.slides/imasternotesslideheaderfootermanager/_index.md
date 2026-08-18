---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Java API リファレンス
description: マスターノートスライドのフッター、日時、ページ番号プレースホルダーとすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

マスターノートスライドのフッター、日時、ページ番号プレースホルダーとすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーの可視性を変更します。 |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーにテキストを設定します。 |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | マスターノートスライドのフッタープレースホルダーとすべての子フッタープレースホルダーの可視性を変更します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | マスターノートスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの可視性を変更します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | マスターノートスライドの日時プレースホルダーとすべての子日時プレースホルダーの可視性を変更します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | マスターノートスライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | マスターノートスライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。 |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーの可視性を変更します。子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダー プレースホルダーを表示し、false - 非表示にします。 |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーにテキストを設定します。子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

マスターノートスライドのフッタープレースホルダーとすべての子フッタープレースホルダーの可視性を変更します。子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示し、false - 非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

マスターノートスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの可視性を変更します。子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示し、false - 非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

マスターノートスライドの日時プレースホルダーとすべての子日時プレースホルダーの可視性を変更します。子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日時プレースホルダーを表示し、false - 非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

マスターノートスライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

マスターノートスライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |