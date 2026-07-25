---
title: MakeRelativeUri()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトと指定された Uri オブジェクトが表す URI の違いを決定します。
type: docs
weight: 352
url: /ja/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) メソッド

現在のオブジェクトと指定された [Uri](../) オブジェクトが表す URI の違いを決定します。

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 比較対象 |

### 戻り値

現在のオブジェクトと **toUri** が表す URI のホスト名とスキームが同じ場合、このメソッドは現在の URI インスタンスに追加したときに **toUri** を生成する相対 [Uri](../) を返します。ホスト名またはスキームが異なる場合、このメソッドは **uri** パラメータを表す [Uri](../) オブジェクトを返します。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)