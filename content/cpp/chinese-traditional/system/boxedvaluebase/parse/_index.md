---
title: Parse()
second_title: Aspose.Slides for C++ API 參考
description: 將指定列舉中具有指定名稱的列舉常數的值裝箱。參數指定在解釋指定列舉常數名稱的字串時是否忽略大小寫。
type: docs
weight: 53
url: /zh-hant/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) 方法


將指定列舉中具有指定名稱的列舉常數的值裝箱。參數指定在解釋指定列舉常數名稱的字串時是否忽略大小寫。

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 指定列舉的類型 |
| str | const [String](../../string/)\& | 列舉常數的名稱，其值將被裝箱 |
| ignoreCase | **bool** | 指定在解釋代表列舉常數名稱的字串時是否忽略大小寫 |

### 回傳值

指向表示指定列舉常數之裝箱值之物件的共享指標

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) 方法


將指定列舉中具有指定名稱的列舉常數的值裝箱。

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 指定列舉的類型 |
| str | const [String](../../string/)\& | 列舉常數的名稱，其值將被裝箱 |

### 回傳值

指向表示指定列舉常數之裝箱值之物件的共享指標

## 參見

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [Object](../../object/)
* 類別 [TypeInfo](../../typeinfo/)
* 類別 [String](../../string/)
* 類別 [BoxedValueBase](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)