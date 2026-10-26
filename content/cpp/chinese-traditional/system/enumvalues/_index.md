---
title: EnumValues
second_title: Aspose.Slides for C++ API 參考文件
description: 提供有關列舉型別 E 常數的中繼資訊。
type: docs
weight: 794
url: /zh-hant/system/enumvalues/
---
## EnumValues 類別

提供有關列舉型別 **E** 常數的中繼資訊。

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| E | 列舉的類型 |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [EnumValues](./enumvalues/)() | 建構實例。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | 回傳包含列舉 **E** 所有名稱的陣列。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | 取得指定列舉之常數名稱的陣列。 |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | 回傳指定列舉的底層類型。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | 回傳指定列舉的底層類型。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | 回傳具有指定名稱之列舉常數的封裝值。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | 回傳具有指定值之列舉常數的封裝值。 |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | 回傳包含列舉 **E** 所有值的陣列。 |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | 回傳指定列舉類型所有值的陣列。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 回傳一個代表指定列舉類型之列舉常數值（具指定名稱）的物件。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | 將指定的 64 位元無號整數值轉換為列舉成員。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 將具有整數值的指定物件轉換為列舉成員。 |
| virtual  [~EnumValues](./~enumvalues/)() | 解構子。 |

## 另見

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)