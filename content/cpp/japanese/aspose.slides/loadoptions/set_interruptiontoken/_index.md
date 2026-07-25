---
title: set_InterruptionToken()
second_title: Aspose.Slides for C++ API リファレンス
description: 割り込み要求を監視するトークンです。
type: docs
weight: 248
url: /ja/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) メソッド


割り込み要求を監視するためのトークンです。

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## 備考


このトークンは [IPresentation](../../ipresentation/) インスタンス全体のライフタイムを管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[InterruptionTokenSource](../../interruptiontokensource/) の [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) メソッドを呼び出すことで割り込まれます。 
## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IInterruptionToken](../../iinterruptiontoken/)
* クラス [LoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)