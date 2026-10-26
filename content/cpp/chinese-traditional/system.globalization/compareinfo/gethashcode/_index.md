---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 參考
description: 根據指定的比較選項取得字串的雜湊碼。
type: docs
weight: 144
url: /zh-hant/system.globalization/compareinfo/gethashcode/
---
## CompareInfo::GetHashCode(const String\&, CompareOptions) const method

根據指定的比較選項取得字串的雜湊碼。

```cpp
virtual int System::Globalization::CompareInfo::GetHashCode(const String &value, CompareOptions options) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 輸入字串。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較選項。 |

### 返回值

雜湊碼。

## CompareInfo::GetHashCode() const method

類似 C# [Object.GetHashCode()](../../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。

```cpp
int System::Globalization::CompareInfo::GetHashCode() const override
```

### 返回值

由對應類別計算得出的雜湊碼值。

## 另請參閱

* 列舉 [CompareOptions](../../compareoptions/)
* 類別 [String](../../../system/string/)
* 類別 [CompareInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)