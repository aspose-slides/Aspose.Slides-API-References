---
title: get_InterruptionToken()
second_title: Aspose.Slides for C++ API リファレンス
description: 中断要求を監視するトークンです。
type: docs
weight: 235
url: /ja/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() メソッド


中断要求を監視するトークンです。

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## 備考


このトークンは [IPresentation](../../ipresentation/) インスタンス全体のライフタイムを管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[IInterruptionTokenSource](../../iinterruptiontokensource/) の [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) メソッドを呼び出すことで中断されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IInterruptionToken](../../iinterruptiontoken/)
* クラス [ILoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)