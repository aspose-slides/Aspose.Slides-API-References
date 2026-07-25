---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() コンストラクタ


コンストラクタ。

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) コンストラクタ


[System.ComponentModel.AsyncCompletedEventArgs](../) クラスの新しいインスタンスを初期化します。

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | 非同期操作中に発生したエラーです。 |
| canceled | **bool** | 非同期操作がキャンセルされたかどうかを示す値です。 |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) メソッドに渡される、オプションのユーザー提供状態オブジェクトです。 |

## 参照

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [AsyncCompletedEventArgs](../)
* クラス [Object](../../../system/object/)
* 名前空間 [System::ComponentModel](../../)
* ライブラリ [Aspose.Slides](../../../)