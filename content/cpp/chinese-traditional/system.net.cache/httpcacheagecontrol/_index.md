---
title: HttpCacheAgeControl
second_title: Aspose.Slides for C++ API 參考
description: CacheAgeControl 用於指定有關快取項目年齡與新鮮度的偏好設定。
type: docs
weight: 53
url: /zh-hant/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl 列舉

CacheAgeControl 用於指定有關快取項目年齡與新鮮度的偏好設定。

```cpp
enum class HttpCacheAgeControl
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | 僅供內部使用。 |
| MinFresh | 1 | 若剩餘時間大於或等於此值指定的時間，則可從快取中取得內容。 |
| MaxAge | 2 | 在內容年齡未超過此值指定的時間前，可從快取中取得內容。 |
| MaxStale | 4 | 內容過期後，於此值指定的時間內仍可從快取中取得。 |
| MaxAgeAndMinFresh | 3 | MaxAge 與 MinFresh。 |
| MaxAgeAndMaxStale | 6 | MaxAge 與 MaxStale。 |

## 另請參閱

* 命名空間 [System::Net::Cache](../)
* 函式庫 [Aspose.Slides](../../)