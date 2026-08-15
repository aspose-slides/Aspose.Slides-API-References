---
title: STDIOStreamPositionPreference
second_title: Aspose.Slides for C++ API 參考
description: "決定在建立封裝器時，當 std::basic_iostream 及其衍生類別具有不同的讀寫位置時，流中的哪個位置最適合作為共用的讀寫位置。"
type: docs
weight: 586
url: /zh-hant/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference 列舉


判斷在 std::basic_iostream 及其衍生類別於建立封裝器時，讀寫位置不同的情況下，哪一個流中的位置最適合作為共用的讀寫位置。

```cpp
enum class STDIOStreamPositionPreference
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| Zero | 0 | Zero 位置將被設定為讀寫位置。 |
| ReadPosition | 1 | gptr 位置將被設定為讀寫位置。 |
| WritePosition | 2 | pptr 位置將被設定為讀寫位置。 |

## 另見

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)