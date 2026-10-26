---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android の Java API リファレンス
description: マスターノートスライドのフッター、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/masternotesslideheaderfootermanager/
---
**継承:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**すべての実装インターフェイス:**  
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)  
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

マスターノートスライドのフッター、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | マスターノートスライドのヘッダープレースホルダーとすべての子ヘッダープレースホルダーの表示状態を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。 |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | マスターノートスライドのヘッダープレースホルダーとすべての子ヘッダープレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。 |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | マスタースライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。 |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

マスターノートスライドのヘッダープレースホルダーとすべての子ヘッダープレースホルダーの表示状態を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダー プレースホルダーを表示し、false - 非表示にします。 |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

マスターノートスライドのヘッダープレースホルダーとすべての子ヘッダープレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示し、false - 非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

マスタースライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示し、false - 非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーの表示状態を変更します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻プレースホルダーを表示し、false - 非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

マスタースライドの日付時刻プレースホルダーとすべての子日付時刻プレースホルダーにテキストを設定します。子プレースホルダーとは、依存ノートスライドに含まれるプレースホルダーを意味します。依存ノートスライドはマスターノートスライドを使用し、依存しています。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |