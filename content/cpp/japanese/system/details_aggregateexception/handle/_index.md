---
title: Handle()
second_title: Aspose.Slides for C++ API リファレンス
description: 各内部例外に対してハンドラ関数を呼び出し、未処理の例外があれば再スローします。
type: docs
weight: 66
url: /ja/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) method

各内部例外に対してハンドラ関数を呼び出し、処理されなかった例外があれば再スローします。

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Exception を受け取り、処理されている場合に true を返す関数。 |

## 備考

すべての例外が処理された場合、メソッドは正常に戻ります。処理されなかった例外が残っている場合は、未処理例外を含む新しい AggregateException がスローされます。

## 参照

* Typedef [Exception](../../exception/)
* クラス [Func](../../func/)
* クラス [Details_AggregateException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)