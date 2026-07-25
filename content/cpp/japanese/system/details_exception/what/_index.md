---
title: what()
second_title: Aspose.Slides for C++ API リファレンス
description: "ExceptionWrapper クラスから呼び出される what() メソッドを実装します。このクラスは std::exception から継承されていないにもかかわらず、派生クラスは protected/private メンバーを使用してロジックを実装できます。このメソッドの実装を ExceptionWrapper に移動すると、そのロジックが壊れる可能性があります。"
type: docs
weight: 105
url: /ja/system/details_exception/what/
---
## Details_Exception::what() const メソッド


[what()](./) メソッドを実装します。このメソッドは [ExceptionWrapper](../../exceptionwrapper/) クラスから呼び出されます。このクラスは std::exception から継承されていないにもかかわらず、派生クラスは protected/private メンバーを使用してロジックを実装できます。このメソッドの実装を [ExceptionWrapper](../../exceptionwrapper/) に移動すると、そのロジックが壊れる可能性があります。

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```


### 戻り値

例外の説明。

## 参照

* クラス [Details_Exception](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)