---
title: HolderInitializer< T, false >
second_title: Aspose.Slides for C++ API リファレンス
description: T が値型である場合の HolderInitializer の特殊化です。使用コンテキストでは、一時オブジェクトへの参照を返すことが許可されており、インスタンスが呼び出し元によってコピーされることが保証されています。そのため、この特殊化はスタブとしてのみ使用され、何もしません。
type: docs
weight: 1652
url: /ja/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct


[HolderInitializer](../holderinitializer/) は T が値型である場合の特殊化です。使用コンテキストでは、一時オブジェクトへの参照を返すことが許可されており、インスタンスが呼び出し元によってコピーされることが保証されています。そのため、この特殊化はスタブとしてのみ使用され、何もしません。

```cpp
template<typename T>class HolderInitializer< T, false >
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |
## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)