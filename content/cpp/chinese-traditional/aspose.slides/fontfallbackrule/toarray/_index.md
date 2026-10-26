---
title: ToArray()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立並傳回此規則所有備援字型的陣列。
type: docs
weight: 144
url: /zh-hant/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() 方法

建立並傳回包含此規則所有備援字型的陣列。

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### 傳回值

[System::String](../../../system/string/) 陣列
## 備註



```cpp
// 建立一個包含字型清單的規則。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 取得所有字型名稱作為陣列。
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) 方法

建立並傳回清單中指定範圍內所有備援字型的陣列。

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | **int32_t** | 要加入的第一個字型的索引。 |
| count | **int32_t** | 要加入的字型數量。 |

### 傳回值

[System::String](../../../system/string/) 陣列
## 備註



```cpp
// 建立一個包含字型清單的規則。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 取得最後兩個字型名稱作為陣列。
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)