---
title: Warning()
second_title: Aspose.Slides for C++ APIリファレンス
description: 警告を受信し、操作を中止すべきかどうかを決定するコールバックメソッドです。
type: docs
weight: 1
url: /ja/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) メソッド

警告を受信し、操作を中止すべきかどうかを決定するコールバックメソッドです。

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | 処理対象の警告。 |

### 戻り値

中止の決定 [ReturnAction](../../returnaction/)。

## 参照

* 列挙体 [ReturnAction](../../returnaction/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IWarningInfo](../../iwarninginfo/)
* クラス [IWarningCallback](../)
* 名前空間 [Aspose::Slides::Warnings](../../)
* ライブラリ [Aspose.Slides](../../../)