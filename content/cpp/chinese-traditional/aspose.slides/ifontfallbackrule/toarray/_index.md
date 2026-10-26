---
title: ToArray()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立並傳回此規則的所有備援字型的陣列。
type: docs
weight: 105
url: /zh-hant/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() 方法


建立並傳回包含此規則所有備援字型的陣列。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### 返回值

[System::String](../../../system/string/) 陣列
## 備註



```cpp
// 建立一個規則，包含字型清單。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//取得所有字型名稱作為陣列
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) 方法


建立並傳回清單中指定範圍內所有備援字型的陣列。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | 要加入的第一個字型的索引。 |
| count | **int32_t** | 要加入的字型數量。 |

### 返回值

[System::String](../../../system/string/) 陣列
## 備註



```cpp
// 建立一個規則，包含字型清單。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//取得最後兩個字型名稱作為陣列。
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [IFontFallBackRule](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)