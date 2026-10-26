---
title: WeakReference<>
second_title: Aspose.Slides C++ API 參考
description: 表示弱參考，允許在仍能刪除該物件的同時引用它。
type: docs
weight: 1522
url: /zh-hant/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> 類別

表示弱參考，允許在仍能刪除該物件的同時引用它。

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | 取得指示目前 WeakReference 物件所參考的物件是否已被刪除。 |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | 取得目前 WeakReference 物件所參考的物件（目標）。 |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 設定目前 WeakReference 物件所參考的物件（目標）。 |
| [WeakReference](./weakreference/)() | 預設建構函式。 |
| [WeakReference](./weakreference/)(std::nullptr_t) | 以 nullptr 為參數的建構函式。 |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 初始化 WeakReference 類別的新實例，參考指定的物件。 |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | 初始化 WeakReference 類別的新實例，參考指定的物件。 |

## 另見

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)