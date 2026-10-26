---
title: CombineMode
second_title: Aspose.Slides for C++ API 參考
description: 指定裁剪區域的結合方式。
type: docs
weight: 170
url: /zh-hant/system.drawing.drawing2d/combinemode/
---
## CombineMode enum


指定裁剪區域的結合方式。

```cpp
enum class CombineMode
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| Replace | 0 | 一個裁剪區域被另一個裁剪區域取代。 |
| Intersect | 1 | 兩個裁剪區域以取交集的方式合併。 |
| Union | 2 | 兩個裁剪區域以取兩者的聯集方式合併。 |
| Xor | 3 | 兩個裁剪區域僅取任一區域所圍的區域（不包括同時被兩個區域覆蓋的部分）來合併。 |
| Exclude | 4 | 兩個裁剪區域以取第一個區域中不與第二個區域相交的區域來合併。 |
| Complement | 5 | 兩個裁剪區域以取第二個區域中不與第一個區域相交的區域來合併。 |

## 另請參閱

* 命名空間 [System::Drawing::Drawing2D](../)
* 函式庫 [Aspose.Slides](../../)