---
title: SetValue()
second_title: Aspose.Slides for C++ API 參考
description: 將屬性值設定為特定物件。
type: docs
weight: 14
url: /zh-hant/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) 方法

將屬性值設定為特定物件。

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 用於寫入屬性。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 屬性要設定的值。 |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) 方法

將屬性值設定為特定物件。

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 用於寫入屬性。 |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 這些是索引屬性的可選索引值。對於非索引屬性，此值應為 null。 |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | 屬性要設定的值。 |

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Object](../../../system/object/)
* 類別 [PropertyInfo](../)
* 命名空間 [System::Reflection](../../)
* 函式庫 [Aspose.Slides](../../../)