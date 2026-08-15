---
title: MemberwiseClone()
second_title: Aspose.Slides for C++ API 參考
description: 使用複製建構子執行成員逐項克隆。
type: docs
weight: 2601
url: /zh-hant/system/memberwiseclone/
---
## System::MemberwiseClone(T *) 函式


使用複製建構子執行成員逐項克隆。

```cpp
template<typename T> SmartPtr<Object> System::MemberwiseClone(T *ptr)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 要以複製建構子建構的類別。子類別資訊將會遺失。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | T * | 指向要克隆之物件的指標。 |

### 回傳值

指向已克隆之物件的指標。

## 另見

* 類別 [SmartPtr](../smartptr/)
* 類別 [Object](../object/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)