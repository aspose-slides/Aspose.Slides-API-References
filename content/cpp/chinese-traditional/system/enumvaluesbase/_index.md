---
title: EnumValuesBase
second_title: Aspose.Slides for C++ API 參考文件
description: 表示列舉類型之中繼資訊的基底類別。
type: docs
weight: 807
url: /zh-hant/system/enumvaluesbase/
---
## EnumValuesBase 類別


此為表示列舉類型之中繼資訊的基底類別。

```cpp
class EnumValuesBase
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | 取得指定列舉中常數名稱的陣列。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | 傳回指定列舉的底層型別。 |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | 傳回包含指定列舉類型所有值的陣列。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 傳回一個物件，該物件代表具有指定名稱之指定列舉類型的列舉常數值。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | 將指定的 64 位元無號整數值轉換為列舉成員。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 將具有整數值的指定物件轉換為列舉成員。 |
## 另請參閱

* 名稱空間 [System](../)
* 函式庫 [Aspose.Slides](../../)