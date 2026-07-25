---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_argumentnullexception/is/
---
## 詳細 ArgumentNullException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_ArgumentNullException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 現在のオブジェクトに対してテストする型を記述する構造体。 |

### 戻り値

True if object is of tagged type or its subclass, false otherwise.

## 備考

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator.

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_ArgumentNullException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)