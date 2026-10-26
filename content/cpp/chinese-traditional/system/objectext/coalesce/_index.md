---
title: Coalesce()
second_title: Aspose.Slides for C++ API 參考
description: 非可為 null 類型的 '??' 運算子翻譯實作。
type: docs
weight: 170
url: /zh-hant/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) 方法

非可為 null 類型的 '??' 運算子翻譯實作。

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T0 | 左側值類型。 |
| T1 | 封裝右側表達式的 lambda 類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | T0 | 左側值。 |
| func | T1 | 右側表達式。 |

### 返回值

如果左側值不為 null，返回左側值；否則計算右側表達式並返回結果。

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) 方法

可為 null 類型的 '??' 運算子翻譯實作。

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T0 | 左側值類型。 |
| T1 | 封裝右側表達式的 lambda 類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | 左側值。 |
| func | T1 | 右側表達式。 |

### 返回值

如果左側值不為 null，返回左側值；否則計算右側表達式並返回結果。

## 另請參閱

* 類別 [ObjectExt](../)
* 類別 [Nullable](../../nullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)