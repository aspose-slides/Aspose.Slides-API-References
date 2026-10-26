---
title: SendWarning()
second_title: Aspose.Slides for C++ API リファレンス
description: receiver が null でない場合、指定された受信者に警告を終了し、receiver が操作の中止を決定した場合は AbortRequestedException をスローします。
type: docs
weight: 27
url: /ja/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) メソッド

If receiver is not null ends warning to a specified receiver and throws the AbortRequestedException if receiver decided to abort a operation.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | 受信オブジェクト [IWarningCallback](../../iwarningcallback/) |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IWarningCallback](../../iwarningcallback/)
* クラス [IWarningInfo](../)
* 名前空間 [Aspose::Slides::Warnings](../../)
* ライブラリ [Aspose.Slides](../../../)