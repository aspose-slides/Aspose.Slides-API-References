---
title: DateTimeStyles
second_title: Aspose.Slides for C++ API 參考文件
description: 定義日期和時間的格式化選項。位元旗標。
type: docs
weight: 456
url: /zh-hant/system.globalization/datetimestyles/
---
## DateTimeStyles 列舉


定義日期和時間的格式化選項。位元旗標。

```cpp
enum class DateTimeStyles : int32_t
```

### Values

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| None | 0 | 預設。 |
| AllowLeadingWhite | 1 | 忽略前置空白字元。 |
| AllowTrailingWhite | 2 | 忽略尾端空白字元。 |
| AllowInnerWhite | 4 | 忽略內部空白字元。 |
| AllowWhiteSpaces | n/a | 忽略所有空白字元。 |
| NoCurrentDateDefault | 8 | 在解析日期/時間字串時，若年/月/日全部缺失，則將預設日期設為 0001/1/1，而非目前的年/月/日。 |
| AdjustToUniversal | 16 | 在解析日期/時間字串時，若存在時區指定詞（"GMT","Z","+xxxx","-xxxx"），我們將根據 GMT 調整解析出的時間。 |
| AssumeLocal | 32 | 如果未提供時區，則使用本地時區。 |
| AssumeUniversal | 64 | 如果未提供時區，則使用 UTC。 |
| RoundtripKind | 128 | 嘗試保留輸入是未指定、本地或 UTC 的狀態。 |

## 另見

* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)