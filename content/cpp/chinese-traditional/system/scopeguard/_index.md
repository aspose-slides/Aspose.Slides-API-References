---
title: ScopeGuard
second_title: Aspose.Slides for C++ API 參考文件
description: 提供在類別實例超出範圍時執行特定 function object 服務的類別。
type: docs
weight: 1886
url: /zh-hant/system/scopeguard/
---
## ScopeGuard struct

提供在類別實例超出範圍時執行特定 function object 的服務類別。

```cpp
template<typename F>class ScopeGuard
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| F | 由 ScopedGuard class 的實例所呼叫的 function object 的類型 |

## 方法

| 方法 | 說明 |
| --- | --- |
| void [Disable](./disable/)() | 停用 guard 呼叫。 |
| [ScopeGuard](./scopeguard/)(F) | 建構一個已設定為呼叫指定 function object 的實例。 |
| [~ScopeGuard](./~scopeguard/)() | 呼叫傳遞給建構函式的 function object。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)