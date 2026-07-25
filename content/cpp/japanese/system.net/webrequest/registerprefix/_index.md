---
title: RegisterPrefix()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI に対して WebRequest の子孫を登録します。
type: docs
weight: 92
url: /ja/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) メソッド

指定された URI に対して [WebRequest](../) の子孫を登録します。

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | URI または URI プレフィックスです。 |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | [WebRequest](../) クラスの新しいインスタンスを作成します。 |

### 戻り値

True は、指定された URI に対して [WebRequest](../) の子孫が正常に登録された場合に返され、そうでない場合は false が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [IWebRequestCreate](../../iwebrequestcreate/)
* クラス [WebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)