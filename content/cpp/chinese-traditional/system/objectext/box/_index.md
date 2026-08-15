---
title: Box()
second_title: Aspose.Slides for C++ API 參考文件
description: 將值類型裝箱以轉換為 Object。列舉類型的實作。
type: docs
weight: 40
url: /zh-hant/system/objectext/box/
---
## ObjectExt::Box(const T\&) 方法

將值類型裝箱以轉換為 [Object](../../object/)。列舉類型的實作。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [Enum](../../enum/) 型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) 值要裝箱。 |

### 返回值

指向保存已裝箱值之物件的智慧指標。

## ObjectExt::Box(const T\&) 方法

將值類型裝箱以轉換為 [Object](../../object/)。非列舉類型的實作。

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 值型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const T\& | 要裝箱的值。 |

### 返回值

指向保存已裝箱值之物件的智慧指標。

## ObjectExt::Box(const T\&) 方法

將 [Nullable](../../nullable/) 類型裝箱以轉換為 [Object](../../object/)。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 值型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const T\& | 要裝箱的值。 |

### 返回值

指向保存已裝箱值之物件的智慧指標。

## ObjectExt::Box(const String\&) 方法

將字串值裝箱。

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要裝箱的值。 |

### 返回值

如果來源字串為 null，則返回裝箱值或 null。

## 另請參閱

* 類別 [SmartPtr](../../smartptr/)
* 類別 [Object](../../object/)
* 類別 [ObjectExt](../)
* 類別 [String](../../string/)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)