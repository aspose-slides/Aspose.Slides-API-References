---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Java API リファレンス
description: マスターノートスライドのフッター、日付・時刻、ページ番号プレースホルダーとすべての子プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/masternotesslideheaderfootermanager/
---
**継承:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)  
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

マスターノートスライドのフッター、日付・時刻、ページ番号プレースホルダーとすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、マスターノートスライドに依存します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーの表示状態を変更します。 |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーにテキストを設定します。 |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | マスタースライドのフッター プレースホルダーとすべての子フッター プレースホルダーの表示状態を変更します。 |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | マスタースライドのページ番号 プレースホルダーとすべての子ページ番号 プレースホルダーの表示状態を変更します。 |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | マスタースライドの日付・時刻 プレースホルダーとすべての子日付・時刻 プレースホルダーの表示状態を変更します。 |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | マスタースライドのフッター プレースホルダーとすべての子フッター プレースホルダーにテキストを設定します。 |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | マスタースライドの日付・時刻 プレースホルダーとすべての子日付・時刻 プレースホルダーにテキストを設定します。 |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーの表示状態を変更します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、マスターノートスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダー プレースホルダーを表示し、false の場合は非表示にします。 |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

マスターノートスライドのヘッダー プレースホルダーとすべての子ヘッダー プレースホルダーにテキストを設定します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、マスターノートスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

マスタースライドのフッター プレースホルダーとすべての子フッター プレースホルダーの表示状態を変更します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、マスターノートスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッター プレースホルダーを表示し、false の場合は非表示にします。 |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

マスタースライドのページ番号 プレースホルダーとすべての子ページ番号 プレースホルダーの表示状態を変更します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、マスターノートスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号 プレースホルダーを表示し、false の場合は非表示にします。 |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

マスタースライドの日付・時刻 プレースホルダーとすべての子日付・時刻 プレースホルダーの表示状態を変更します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、マスターノートスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付・時刻 プレースホルダーを表示し、false の場合は非表示にします。 |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

マスタースライドのフッター プレースホルダーとすべての子フッター プレースホルダーにテキストを設定します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、マスターノートスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

マスタースライドの日付・時刻 プレースホルダーとすべての子日付・時刻 プレースホルダーにテキストを設定します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、マスターノートスライドに依存します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |