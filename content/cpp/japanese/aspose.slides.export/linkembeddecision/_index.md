---
title: LinkEmbedDecision
second_title: Aspose.Slides for C++ API リファレンス
description: 保存時にオブジェクトがどのように処理されるかを決定します。
type: docs
weight: 911
url: /ja/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision 列挙型

保存時にオブジェクトがどのように処理されるかを決定します。

```cpp
enum class LinkEmbedDecision
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Link | 0 | オブジェクトは外部に保存され、URLで参照されます |
| Embed | 1 | 可能であれば、オブジェクトは生成されたファイルに埋め込まれるべきです。埋め込みが不可能な場合、GetUrl が呼び出され、結果に応じてオブジェクトは URL で参照されるか、無視されます |
| Ignore | 2 | オブジェクトは無視されます |

## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)