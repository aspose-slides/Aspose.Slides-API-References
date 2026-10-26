---
title: EventHandler
second_title: Aspose.Slides for C++ API リファレンス
description: "イベントに反応し、処理するメソッドを表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。決して System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 3706
url: /ja/system/eventhandler/
---
## EventHandler typedef

イベントに反応し、処理するメソッドを表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。決して [System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)