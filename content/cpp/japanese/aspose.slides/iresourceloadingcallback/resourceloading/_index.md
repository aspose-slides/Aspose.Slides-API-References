---
title: ResourceLoading()
second_title: Aspose.Slides for C++ API リファレンス
description: 外部リソースの読み込みを調整するコールバックメソッド。
type: docs
weight: 1
url: /ja/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) メソッド

外部リソースの読み込みを調整するコールバックメソッド。

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | ロード中のリソースデータ [IResourceLoadingArgs](../../iresourceloadingargs/)。 |

### 戻り値

リソースの読み込み決定 [ResourceLoadingAction](../../resourceloadingaction/)。

## 参照

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IResourceLoadingArgs](../../iresourceloadingargs/)
* クラス [IResourceLoadingCallback](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)