---
title: Enter()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定的物件上取得獨佔鎖。
type: docs
weight: 1
url: /zh-hant/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) 方法

在指定的物件上取得獨佔鎖。

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 用於取得監視器鎖的物件。 |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) 方法

在指定的物件上取得獨佔鎖，並原子性地設定一個指示是否已取得鎖的值。

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [Monitor](../)
* 命名空間 [System::Threading](../../)
* Library [Aspose.Slides](../../../)