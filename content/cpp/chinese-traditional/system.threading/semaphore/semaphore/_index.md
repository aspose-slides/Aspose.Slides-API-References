---
title: Semaphore()
second_title: Aspose.Slides for C++ API 參考
description: 建立未命名的訊號量。
type: docs
weight: 1
url: /zh-hant/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) 建構函式

建立未命名的訊號量。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| initialCount | int | 活動條目的初始計數。 |
| maximumCount | int | 允許的條目最大計數。 |

## Semaphore::Semaphore(int, int, const String\&) 建構函式

建立已命名的訊號量。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| initialCount | int | 活動條目的初始計數。 |
| maximumCount | int | 允許的條目最大計數。 |
| name | const [String](../../../system/string/)\& | [Semaphore](../) 名稱。 |

## Semaphore::Semaphore(int, int, const String\&, bool\&) 建構函式

建立已命名的訊號量。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| initialCount | int | 活動條目的初始計數。 |
| maximumCount | int | 允許的條目最大計數。 |
| name | const [String](../../../system/string/)\& | [Semaphore](../) 名稱。 |
| createdNew | **bool**\& | 參考變數，如果建立了 semaphore 則設為 true，若使用了具有相同名稱的已存在 semaphore 則設為 false。 |

## 另請參閱

* 類別 [Semaphore](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)