---
title: CachedEnumerable()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 1
url: /ja/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) constructor




```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | 次の項目が必要になったときに呼び出されるコールバック。項目がなくなった場合は false を返し、次の項目を挿入するには Add メソッドを使用してください。 |

## 参照

* クラス [Func](../../../system/func/)
* クラス [CachedEnumerable](../)
* 名前空間 [System::Linq::Details](../../)
* ライブラリ [Aspose.Slides](../../../)