---
title: FastToAscii()
second_title: Aspose.Slides for C++ API 參考文件
description: 嘗試將 String 轉換為 ASCII 字串。
type: docs
weight: 794
url: /zh-hant/system/string/fasttoascii/
---
## String::FastToAscii(char, int) const 方法


嘗試將 [String](../) 轉換為 ASCII 字串。

```cpp
int System::String::FastToAscii(char buffer[], int buffer_size) const
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | char | 用於儲存結果字串的緩衝區。 |
| buffer_size | int | [Buffer](../../buffer/) 的大小。 |

### 返回值

結果字串長度，若 [String](../) 不是 ASCII 字串則返回 -1。

## 參見

* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)