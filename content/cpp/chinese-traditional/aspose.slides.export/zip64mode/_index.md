---
title: Zip64Mode
second_title: Aspose.Slides for C++ API 參考
description: 指定何時對 OpenXML 檔案使用 ZIP64 格式延伸。
type: docs
weight: 1119
url: /zh-hant/aspose.slides.export/zip64mode/
---
## Zip64Mode 列舉

指定何時對 OpenXML 檔案使用 ZIP64 格式延伸。

```cpp
enum class Zip64Mode
```

### 值

| 名稱 | 數值 | 描述 |
| --- | --- | --- |
| Never | 0 | 不使用 ZIP64 格式延伸。 |
| IfNecessary | 1 | 如有必要則使用 ZIP64 格式延伸。 |
| Always | 2 | 總是使用 ZIP64 格式延伸。 |

## 備註

OpenXML 檔案是一個 ZIP 壓縮檔，其未壓縮檔案大小、壓縮檔案大小以及整個壓縮檔的總大小上限為 4 GB (2^32 位元組)，且壓縮檔內的檔案數上限為 65,535 (2^16-1) 個。ZIP64 格式延伸將上限提升至 2^64。

## 另見

* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)