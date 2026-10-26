---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.io/details_invaliddataexception/is/
---
## Details_InvalidDataException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_InvalidDataException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 現在のオブジェクトに対してテストする型を記述する構造体 |

### 戻り値

True if object is of tagged type or its subclass, false otherwise.

## 備考

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 

## 関連項目

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_InvalidDataException](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)