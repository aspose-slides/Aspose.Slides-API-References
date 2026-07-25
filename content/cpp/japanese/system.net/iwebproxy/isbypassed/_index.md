---
title: IsBypassed()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたホストに対してプロキシを使用すべきでないかを示す値を返します。
type: docs
weight: 40
url: /ja/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) メソッド

指定されたホストに対してプロキシを使用すべきでないかを示す値を返します。

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 確認するホスト URI。 |

### 戻り値

True when the proxy server must not be used, otherwise false.

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [IWebProxy](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)