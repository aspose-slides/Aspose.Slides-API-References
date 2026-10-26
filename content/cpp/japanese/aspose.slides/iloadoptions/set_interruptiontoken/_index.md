---
title: set_InterruptionToken()
second_title: Aspose.Slides の C++ API リファレンス
description: 中断要求を監視するためのトークンです。
type: docs
weight: 248
url: /ja/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) メソッド

このトークンは中断要求を監視するためのものです。

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## 備考

このトークンは [IPresentation](../../ipresentation/) インスタンスの全体的なライフタイムを管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[IInterruptionTokenSource](../../iinterruptiontokensource/) の [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) メソッドを呼び出すことで中断されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IInterruptionToken](../../iinterruptiontoken/)
* クラス [ILoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)