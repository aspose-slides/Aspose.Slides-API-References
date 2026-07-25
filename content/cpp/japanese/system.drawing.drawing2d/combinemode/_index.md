---
title: CombineMode
second_title: Aspose.Slides for C++ API リファレンス
description: クリッピング領域がどのように結合されるかを指定します。
type: docs
weight: 170
url: /ja/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

クリッピング領域がどのように結合されるかを指定します。

```cpp
enum class CombineMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Replace | 0 | あるクリッピング領域が別の領域に置き換えられます。 |
| Intersect | 1 | 2つのクリッピング領域は交差部分を取ることで結合されます。 |
| Union | 2 | 2つのクリッピング領域は両方の合集合を取ることで結合されます。 |
| Xor | 3 | 2つのクリッピング領域は、どちらか一方の領域にのみ含まれる領域を取り、両方に含まれる領域は除外して結合されます。 |
| Exclude | 4 | 2つのクリッピング領域は、第二の領域と交差しない最初の領域の領域を取ることで結合されます。 |
| Complement | 5 | 2つのクリッピング領域は、第一の領域と交差しない第二の領域の領域を取ることで結合されます。 |

## 参照

* 名前空間 [System::Drawing::Drawing2D](../)
* ライブラリ [Aspose.Slides](../../)