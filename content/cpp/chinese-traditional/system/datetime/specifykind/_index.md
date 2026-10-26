---
title: SpecifyKind()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構一個新的 DateTime 物件，該物件表示與指定的 DateTime 物件相同的刻度數，且根據參數 kind 的指定，表示本地時間、UTC 時間或兩者皆非。
type: docs
weight: 833
url: /zh-hant/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) 方法


建構一個新的 [DateTime](../) 物件，該物件表示與指定的 [DateTime](../) 物件相同的刻度數，且根據參數 **kind** 的指定，表示本地時間、UTC 時間或兩者皆非。

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [DateTime](../) | 用於複製刻度數的 [DateTime](../) 物件 |
| kind | [DateTimeKind](../../datetimekind/) | 指定新物件是否應表示本地時間、UTC 時間或兩者皆非。 |

### 回傳值

一個新的 [DateTime](../) 物件，表示與 **value** 相同的刻度數，且其 DateTimeKind 值由 **kind** 指定。

## 另請參閱

* Enum [DateTimeKind](../../datetimekind/)
* 類別 [DateTime](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)