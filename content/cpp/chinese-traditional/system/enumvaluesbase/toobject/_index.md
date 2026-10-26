---
title: ToObject()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的 64 位元無號整數值轉換為列舉成員。
type: docs
weight: 40
url: /zh-hant/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) method

將指定的 64 位元無號整數值轉換為列舉成員。

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 要傳回的列舉型別。 |
| value | **uint64_t** | 要轉換為列舉成員的值。 |

### 傳回值

一個設定為該值的列舉實例。

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) method

將具有整數值的指定物件轉換為列舉成員。

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 要傳回的列舉型別。 |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 要轉換為列舉成員的值。 |

### 傳回值

其值為該值的列舉物件。

## 相關參考

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [Object](../../object/)
* 類別 [TypeInfo](../../typeinfo/)
* 類別 [EnumValuesBase](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)