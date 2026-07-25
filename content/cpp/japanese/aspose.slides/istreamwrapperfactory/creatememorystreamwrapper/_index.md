---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: MemoryStream ラッパーを作成します。
type: docs
weight: 1
url: /ja/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() メソッド

MemoryStream ラッパーを作成します。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### 戻り値

COM インターフェイス [IStreamWrapper](../../istreamwrapper/) 用のストリームラッパー

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) メソッド

指定されたバイト配列に基づいて MemoryStream ラッパーを作成します。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列 **uint8_t**[] |

### 戻り値

COM インターフェイス [IStreamWrapper](../../istreamwrapper/) 用のストリームラッパー

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [IStreamWrapper](../../istreamwrapper/)
* クラス [IStreamWrapperFactory](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)