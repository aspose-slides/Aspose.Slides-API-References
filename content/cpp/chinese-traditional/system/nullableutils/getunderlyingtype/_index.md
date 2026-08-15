---
title: GetUnderlyingType()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回指定可空類型的基礎類型參數。
type: docs
weight: 1
url: /zh-hant/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) 方法


返回指定可空類型的基礎類型參數。

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | 描述封閉通用可空類型的 System.Type 物件。 |

### 返回值

如果 nullableType 參數是封閉通用可空類型，則返回 nullableType 參數的類型參數；否則，null

## 另請參閱

* 類別 [TypeInfo](../../typeinfo/)
* 類別 [NullableUtils](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)