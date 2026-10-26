---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides の Java API リファレンス
description: プレゼンテーションのすべてのフッター、日付時刻、ページ番号プレースホルダーの動作を保持するマネージャーを表します。
type: docs
url: /ja/com.aspose.slides/ipresentationheaderfootermanager/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

プレゼンテーションのすべてのフッター、日付時刻、ページ番号プレースホルダーの動作を保持するマネージャーを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | ノートマスター、ノートスライド、ハンドアウトマスターを含む、すべてのヘッダープレースホルダーの表示/非表示を変更します。 |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | マスタースライド、レイアウトスライド、スライドを含む、すべてのフッタープレースホルダーの表示/非表示を変更します。 |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | マスタースライド、レイアウトスライド、スライドを含む、すべてのページ番号プレースホルダーの表示/非表示を変更します。 |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | マスタースライド、レイアウトスライド、スライドを含む、すべての日付時刻プレースホルダーの表示/非表示を変更します。 |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | ノートマスター、ノートスライド、ハンドアウトマスターを含む、すべてのヘッダープレースホルダーにテキストを設定します。 |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | マスタースライド、レイアウトスライド、スライドを含む、すべてのフッタープレースホルダーにテキストを設定します。 |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | マスタースライド、レイアウトスライド、スライドを含む、すべての日付時刻プレースホルダーにテキストを設定します。 |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | すべてのタイトルスライドおよび最初のレイアウトスライドに対して、フッター、日付時刻、ページ番号プレースホルダーの表示/非表示を変更します。 |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

ノートマスター、ノートスライド、ハンドアウトマスターを含む、すべてのヘッダープレースホルダーの表示/非表示を変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ヘッダープレースホルダーを表示にし、false の場合は非表示にします。 |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

マスタースライド、レイアウトスライド、スライドを含む、すべてのフッタープレースホルダーの表示/非表示を変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - フッタープレースホルダーを表示にし、false の場合は非表示にします。 |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

マスタースライド、レイアウトスライド、スライドを含む、すべてのページ番号プレースホルダーの表示/非表示を変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - ページ番号プレースホルダーを表示にし、false の場合は非表示にします。 |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

マスタースライド、レイアウトスライド、スライドを含む、すべての日付時刻プレースホルダーの表示/非表示を変更します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - 日付時刻プレースホルダーを表示にし、false の場合は非表示にします。 |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

ノートマスター、ノートスライド、ハンドアウトマスターを含む、すべてのヘッダープレースホルダーにテキストを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

マスタースライド、レイアウトスライド、スライドを含む、すべてのフッタープレースホルダーにテキストを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

マスタースライド、レイアウトスライド、スライドを含む、すべての日付時刻プレースホルダーにテキストを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 設定するテキスト。 |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

すべてのタイトルスライドおよび最初のレイアウトスライドに対して、フッター、日付時刻、ページ番号プレースホルダーの表示/非表示を変更します。タイトルスライド – 最初のレイアウトスライドに基づくスライド（この最初のレイアウトの種類に関係なく）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isVisible | boolean | true - プレースホルダーを表示にし、false の場合は非表示にします。 |