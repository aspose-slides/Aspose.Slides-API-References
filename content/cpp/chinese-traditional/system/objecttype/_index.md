---
title: ObjectType
second_title: Aspose.Slides for C++ API 參考
description: 提供實作物件類型取得器的靜態方法。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。
type: docs
weight: 1158
url: /zh-hant/system/objecttype/
---
## ObjectType 類別

提供實作物件類型取得器的靜態方法。這是一個沒有實例服務的靜態類型。絕不應以任何方式建立其實例。

```cpp
class ObjectType
```

## 方法

| Method | Description |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | 實作 typeof() 轉譯。針對智慧指標的超載。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | 實作 typeof() 轉譯。針對結構的超載。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | 實作 typeof() 轉譯。針對例外的超載。 |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | 實作 typeof() 轉譯。針對基本類型的超載。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | 實作 typeof() 轉譯。針對 [Nullable](../nullable/) 類型的超載。 |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 實作 typeof() 轉譯。針對基本類型的超載。 |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 實作 typeof() 轉譯。針對列舉類型的超載。 |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 實作 typeof() 轉譯。針對結構與指標的超載。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 實作 typeof() 轉譯。針對 [Nullable](../nullable/) 的超載。 |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 實作 typeof() 轉譯。針對 MutlicastDelegate 的超載。 |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 實作 typeof() 轉譯。針對結構與指標的超載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | 實作 typeof() 轉譯。針對 string 類型的超載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 實作 typeof() 轉譯。針對 **uint8_t** 的超載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 實作 typeof() 轉譯。針對 **uint8_t** 的超載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 實作 typeof() 轉譯。針對 **uint8_t** 的超載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 實作 typeof() 轉譯。針對 **uint8_t** 的超載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 實作 typeof() 轉譯。針對 **uint8_t** 的超載。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 實作 typeof() 轉譯。針對 **uint8_t** 的超載。 |

## 另請參閱

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)