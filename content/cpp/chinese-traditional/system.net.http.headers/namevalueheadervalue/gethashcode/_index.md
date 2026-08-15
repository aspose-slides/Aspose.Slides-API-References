---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 參考
description: 類似於 C# Object.GetHashCode() 方法。啟用自訂物件的雜湊。
type: docs
weight: 53
url: /zh-hant/system.net.http.headers/namevalueheadervalue/gethashcode/
---
## NameValueHeaderValue::GetHashCode() const 方法

類似於 C# [Object.GetHashCode()](../../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。

```cpp
int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode() const override
```

### 傳回值

雜湊碼值，由對應的類別計算。

## NameValueHeaderValue::GetHashCode(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) 方法

傳回所有集合項目的雜湊碼。

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue 類別實例的集合。 |

### 傳回值

所有集合項目的雜湊碼。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [NameValueHeaderValue](../)
* 類別 [ObjectCollection](../../objectcollection/)
* 命名空間 [System::Net::Http::Headers](../../)
* 程式庫 [Aspose.Slides](../../../)