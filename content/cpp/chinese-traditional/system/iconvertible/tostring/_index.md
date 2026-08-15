---
title: ToString()
second_title: Aspose.Slides for C++ API 參考
description: "將此實例的值轉換為等效的 System::String，使用指定的特定文化格式資訊。"
type: docs
weight: 196
url: /zh-hant/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) 方法

將此實例的值轉換為等效的 [System::String](../../string/)，使用指定的特定文化格式資訊。

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 提供文化特定格式資訊的 [System::IFormatProvider](../../iformatprovider/) 介面實作。 |

### 回傳值

等同於此實例值的 [System::String](../../string/) 例項。

## IConvertible::ToString() const 方法

C# [Object.ToString()](../../object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。

```cpp
virtual String System::Object::ToString() const
```

### 回傳值

[String](../../string/) 由最終類別提供的表示。

## 另請參閱

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [IConvertible](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)