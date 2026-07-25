---
title: MakeRelative()
second_title: Aspose.Slides for C++ API リファレンス
description: 2つの Uri インスタンス間の差異を決定します。
type: docs
weight: 365
url: /ja/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) メソッド

2つの [Uri](../) インスタンス間の差異を決定します。

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 現在の URI と比較する URI |

### 戻り値

現在のオブジェクトと **toUri** が表す URI のホスト名とスキームが同じ場合、このメソッドは現在の URI インスタンスに付加したときに **toUri** になる相対的な [Uri](../) を表す [String](../../string/) を返します。ホスト名またはスキームが異なる場合、このメソッドは **uri** パラメータを表す [String](../../string/) を返します。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Uri](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)