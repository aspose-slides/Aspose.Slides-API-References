---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.io/details_fileloadexception/is/
---
## Details_FileLoadException::Is(const System::TypeInfo\&) const method

```cpp
bool System::IO::Details_FileLoadException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) は、現在のオブジェクトに対してテストする型を記述する構造体です。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスの場合はTrue、そうでない場合はfalse。

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の類似です。

## 関連項目

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_FileLoadException](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)