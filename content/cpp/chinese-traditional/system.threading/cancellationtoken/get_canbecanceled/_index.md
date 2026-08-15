---
title: get_CanBeCanceled()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得此代幣是否能處於已取消狀態。
type: docs
weight: 27
url: /zh-hant/system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled() const 方法

取得此代幣是否能處於已取消狀態。

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```

### 回傳值

true if this token is capable of being in the canceled state; otherwise, false.

## 備註

由 [CancellationTokenSource](../../cancellationtokensource/) 建立的代幣會返回 true，而 None 代幣則永遠返回 false。

## 另請參閱

* 類別 [CancellationToken](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)