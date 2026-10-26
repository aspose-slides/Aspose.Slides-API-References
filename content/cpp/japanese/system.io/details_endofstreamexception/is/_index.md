---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.io/details_endofstreamexception/is/
---
## Details_EndOfStreamException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_EndOfStreamException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 構造体。現在のオブジェクトがテスト対象とする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでなければ false。

## 備考

オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の `is` 演算子の類似です。

## 関連項目

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_EndOfStreamException](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)