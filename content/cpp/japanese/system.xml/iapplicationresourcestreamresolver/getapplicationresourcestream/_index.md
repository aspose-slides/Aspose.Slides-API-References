---
title: GetApplicationResourceStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI からアプリケーションリソースストリームを返します。
type: docs
weight: 1
url: /ja/system.xml/iapplicationresourcestreamresolver/getapplicationresourcestream/
---
## IApplicationResourceStreamResolver::GetApplicationResourceStream(SharedPtr\<Uri\>) メソッド


指定された URI からアプリケーションリソースストリームを返します。

```cpp
virtual SharedPtr<IO::Stream> System::Xml::IApplicationResourceStreamResolver::GetApplicationResourceStream(SharedPtr<Uri> relativeUri)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| relativeUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 相対 URI。 |

### 戻り値

アプリケーションリソースストリーム。

## 関連項目

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [Uri](../../../system/uri/)
* クラス [IApplicationResourceStreamResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)