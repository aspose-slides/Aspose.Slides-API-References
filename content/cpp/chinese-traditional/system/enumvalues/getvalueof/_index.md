---
title: GetValueOf()
second_title: Aspose.Slides for C++ API 參考
description: 傳回具指定名稱之列舉常數的封裝值。
type: docs
weight: 53
url: /zh-hant/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const 方法


傳回具指定名稱之列舉常數的封裝值。

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 列舉常數的名稱 |
| ignoreCase | **bool** | 指定在解讀列舉常數名稱時是否應忽略大小寫 |

### 回傳值

傳回在 **str** 中指定之列舉常數的封裝值。

## EnumValues::GetValueOf(long) const 方法


傳回具指定值之列舉常數的封裝值。

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| val | long | 列舉常數的值 |

### 回傳值

傳回在 **str** 中指定的 vakye 的列舉常數的封裝值。

## 參見

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [Object](../../object/)
* 類別 [String](../../string/)
* 類別 [EnumValues](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)