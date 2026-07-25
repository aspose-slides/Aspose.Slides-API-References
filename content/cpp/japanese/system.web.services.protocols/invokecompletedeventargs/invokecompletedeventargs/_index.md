---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 14
url: /ja/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | 非同期操作中に発生した任意のエラー。 |
| cancelled | **bool** | 非同期操作がキャンセルされたかどうかを示す値。 |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) メソッドに渡されるオプションのユーザー提供状態オブジェクト。 |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 非同期操作の結果のコレクション。 |

## 関連項目

* 型定義 [Exception](../../../system/exception/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Object](../../../system/object/)
* クラス [InvokeCompletedEventArgs](../)
* 名前空間 [System::Web::Services::Protocols](../../)
* ライブラリ [Aspose.Slides](../../../)