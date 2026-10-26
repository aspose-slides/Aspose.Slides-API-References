---
title: GetValue()
second_title: Aspose.Slides C++ API 參考
description: 取得特定物件的屬性值。
type: docs
weight: 1
url: /zh-hant/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) 方法


取得特定物件的屬性值。

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 用於讀取屬性。 |

### 傳回值

指定物件之指定屬性的值。

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) 方法


取得特定物件的屬性值。

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 用於讀取屬性。 |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | 這些是索引屬性的可選索引值。對於非索引屬性，該值應為 null。 |

### 傳回值

指定物件之指定屬性的值。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [Object](../../../system/object/)
* 類別 [PropertyInfo](../)
* 命名空間 [System::Reflection](../../)
* 函式庫 [Aspose.Slides](../../../)