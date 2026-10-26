---
title: get_InterruptionToken()
second_title: Aspose.Slides for C++ API リファレンス
description: 割り込み要求を監視するトークンです。
type: docs
weight: 235
url: /ja/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() メソッド

このトークンは割り込み要求を監視するためのものです。

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## 備考

このトークンは [IPresentation](../../ipresentation/) インスタンスの全体のライフタイムを管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[InterruptionTokenSource](../../interruptiontokensource/) の [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) メソッドを呼び出すことで割り込みされます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IInterruptionToken](../../iinterruptiontoken/)
* クラス [LoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)