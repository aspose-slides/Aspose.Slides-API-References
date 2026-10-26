---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android の Java API リファレンス
description: マスターノートスライドのフッター、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

マスターノートスライドのフッター、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを指します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーの可視性を変更します。 |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーにテキストを設定します。 |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | マスターノートスライドのフッター プレースホルダーとすべての子フッター プレースホルダーの可視性を変更します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | マスターノートスライドのページ番号 プレースホルダーとすべての子ページ番号 プレースホルダーの可視性を変更します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | マスターノートスライドの日付時刻 プレースホルダーとすべての子日付時刻 プレースホルダーの可視性を変更します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | マスターノートスライドのフッター プレースホルダーとすべての子フッター プレースホルダーにテキストを設定します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | マスターノートスライドの日付時刻 プレースホルダーとすべての子日付時刻 プレースホルダーにテキストを設定します。 |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーの可視性を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを指します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダー プレースホルダーを表示し、false - 非表示にします。 |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを指します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

マスターノートスライドのフッター プレースホルダーとすべての子フッター プレースホルダーの可視性を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを指します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッター プレースホルダーを表示し、false - 非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

マスターノートスライドのページ番号 プレースホルダーとすべての子ページ番号 プレースホルダーの可視性を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを指します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号 プレースホルダーを表示し、false - 非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

マスターノートスライドの日付時刻 プレースホルダーとすべての子日付時刻 プレースホルダーの可視性を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを指します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻 プレースホルダーを表示し、false - 非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

マスターノートスライドのフッター プレースホルダーとすべての子フッター プレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを指します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

マスターノートスライドの日付時刻 プレースホルダーとすべての子日付時刻 プレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを指します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |