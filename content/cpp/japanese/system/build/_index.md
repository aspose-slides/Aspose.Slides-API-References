---
title: Build()
second_title: Aspose.Slides for C++ API リファレンス
description: 直接所有権でオブジェクトを構築します。
type: docs
weight: 2289
url: /ja/system/build/
---
## System::Build(Args\&&...) 関数


直接所有権でオブジェクトを構築します。

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### テンプレート パラメーター

| Parameter | Description |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Arguments to forward to object constructor |

### 戻り値

ObjectBuilder configured for direct object construction
## 備考



[Object](../object/) construction must be finished with [Get()](../get/) call 

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)